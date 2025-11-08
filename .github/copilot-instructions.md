# Copilot Instructions for Arte y Belleza

## Project Overview

Arte y Belleza is a cosmetology-focused project that includes:
- An eBook landing page about beauty transformation
- A React-based admin panel for managing content
- A chatbot configuration for WhatsApp and Instagram sales automation

## Technology Stack

- **Frontend**: React (JSX), HTML5, Tailwind CSS
- **Languages**: JavaScript, Spanish (primary language for content)
- **Platform Integration**: WhatsApp, Instagram bot flows
- **Design**: Google Fonts (Playfair Display, Poppins)

## Coding Conventions

### JavaScript/React
- Use functional components with hooks (useState, etc.)
- Import lucide-react icons for UI elements
- Follow modern ES6+ syntax
- Use descriptive variable names in camelCase

### HTML/CSS
- Use Tailwind CSS utility classes for styling
- Define CSS custom properties in `:root` for theming
- Color scheme: Aqua (#18c5d8), Black (#232323), White (#FFFFFF)
- Maintain responsive design with mobile-first approach

### Spanish Language
- All user-facing content should be in Spanish
- Use professional tone for beauty/cosmetology context
- Maintain consistent terminology across files

## File Structure

- `AdminPanel.jsx` - Admin interface component
- `landing_el_arte_transformador_Version2_blanco_celeste_negro (1).html` - Landing page
- `bot_ventas_ebook_whatsapp_insta.json` - Chatbot configuration for sales
- `README.md` - Project documentation

## Development Guidelines

### When working on AdminPanel.jsx
- Maintain the existing import structure with lucide-react icons
- Keep the component state management pattern
- Ensure accessibility for admin operations

### When working on the landing page
- Preserve the color scheme defined in CSS variables
- Maintain the Playfair Display font for headings
- Keep Tailwind CDN integration
- Ensure responsive design is maintained

### When working on the bot configuration
- Follow the JSON flow structure
- Maintain the conversation flow logic (inicio → info → compra)
- Keep WhatsApp and Instagram platform compatibility
- Preserve the FAQ structure
- Update prices and payment links only when explicitly requested

## Best Practices

1. **Minimal Changes**: Make surgical, precise modifications
2. **No Breaking Changes**: Preserve existing functionality unless fixing bugs
3. **Spanish Content**: All customer-facing text must be in Spanish
4. **Responsive Design**: Test changes on mobile and desktop viewports
5. **Color Consistency**: Use defined CSS variables for colors
6. **Icon Usage**: Use lucide-react icons consistently

## Testing

- Manually test any UI changes in a browser
- Verify responsive behavior for mobile devices
- Test bot conversation flows end-to-end
- Ensure Spanish text reads naturally

## Build Process

This project does not currently have a formal build process. Files are served directly:
- React JSX components may need transpilation for production use
- HTML files can be opened directly in a browser
- JSON configuration is used as-is by the bot platform

## Notes

- No package.json exists yet - this is a lightweight project
- No automated tests are configured
- Focus on maintaining simplicity and ease of deployment
