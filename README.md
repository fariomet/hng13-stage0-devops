# Name: Faridat Suleiman

# Slack Username: Jazzmin.jsx

# Project Description: Accessible Profile Card Component
A responsive, accessible profile card component built with semantic HTML, modern CSS, and vanilla JavaScript.

Domain: https://hng13-stage0-devops.vercel.app/

## Features

- **Semantic HTML**: Proper use of semantic elements for accessibility
- **Responsive Design**: Mobile-first approach that adapts to all screen sizes
- **Accessibility**: Full keyboard navigation, ARIA labels, and focus indicators
- **Real-time Updates**: Current time displayed in milliseconds with live updates
- **Security**: Social links open safely with `rel="noopener noreferrer"`

## Project Structure
profile-card-page/
├──Image

   └──avatar.jpg
   
├── index.html # Main HTML file with embedded CSS and JS

└── README.md # Project documentation
## Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for enhanced testing)

### Installation

1. **Clone or download** the project files to your local machine

2. **Open the HTML file** in your web browser:
   - Double-click the `index.html` file, OR
   - Right-click and select "Open with" your preferred browser

Testing the Component:
Automated Testing
The component includes data-testid attributes for all major elements:

test-profile-card - Main container

test-user-name - User's name

test-user-bio - User biography

test-user-time - Current time in milliseconds

test-user-avatar - Profile image

test-user-social-links - Social media links container

test-user-social-* - Individual social links

test-user-hobbies - Hobbies list

test-user-dislikes - Dislikes list

Manual Testing Checklist
Responsive Behavior

Resize browser window or use device emulation

Verify layout adapts from mobile to desktop

Keyboard Navigation

Tab through all interactive elements

Verify focus indicators are visible

Test social link activation with Enter key

Accessibility

Use screen reader to verify semantic structure

Check color contrast ratios

Verify images have proper alt text

Functionality

Confirm time updates every 100ms

Test social links open in new tabs

Verify all required elements are present

Browser Compatibility
Chrome 60+

Firefox 55+

Safari 12+

Edge 79+

Customization
Styling
Modify CSS custom properties in the :root selector to change colors, spacing, and other design tokens.

Content
Update the HTML content within each section to match your user profile information.

Avatar
Replace the placeholder image URL with your own profile image.

Technical Details
HTML: Semantic elements with proper landmark regions

CSS: Mobile-first responsive design with CSS Grid and Flexbox

JavaScript: Vanilla JS for time updates, no external dependencies

Performance: Efficient time updates with 100ms intervals

License
This project is open source and available under the MIT License.


## Code Explanation

### HTML Structure
- **`<article>`**: Used as the main container since it represents a self-contained composition
- **`<figure>` and `<figcaption>`**: Semantic way to present the avatar image with description
- **`<nav>`**: Properly marks the social links as a navigation region
- **`<section>`**: Groups related content (hobbies and dislikes)
- **`data-testid` attributes**: Added exactly as specified for automated testing

### CSS Approach
- **Mobile-first**: Base styles for mobile, media queries for larger screens
- **CSS Custom Properties**: Variables for consistent theming
- **Flexbox/Grid**: Modern layout techniques for responsiveness
- **Accessibility**: Focus styles, proper contrast, and readable typography

### JavaScript Functionality
- **`updateCurrentTime()`**: Gets current milliseconds and updates the display
- **`setInterval()`**: Updates time every 100ms for reasonable accuracy without performance issues
- **Vanilla JS**: No external libraries, pure JavaScript implementation

This implementation follows all specified requirements while maintaining accessibility, responsiveness, and clean code structure.
