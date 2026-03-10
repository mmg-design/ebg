# Website Design System

## Core Workflow

When provided a reference screenshot and optional CSS styles, generate a complete website recreation following this process:

1. **Analyze** the reference image thoroughly - layout, typography, spacing, colors, components
2. **Build** initial HTML file with all content and styling
3. **Screenshot** the output and compare against reference
4. **Iterate** by identifying specific gaps and making targeted improvements
5. **Repeat** steps 3-4 until achieving 95%+ visual fidelity

Never stop at first draft. Always complete the verification loop.

## Technical Defaults

- **Format**: Single self-contained HTML file with embedded CSS and JS
- **Styling**: Tailwind CSS utility classes preferred, vanilla CSS when needed
- **Responsiveness**: Mobile-first, test at 320px, 768px, 1024px, 1440px breakpoints
- **Performance**: Optimize images, minimize code, clean structure
- **Accessibility**: WCAG 2.1 AA compliance, proper contrast ratios, semantic HTML
- **Browser Support**: Modern browsers, graceful degradation

## Design Quality Standards

- **Typography**: Consistent hierarchy, proper line-height (1.4-1.6), readable font sizes (16px+ body)
- **Spacing**: Systematic padding/margins using 8px grid system
- **Colors**: Maintain brand consistency, ensure 4.5:1 contrast minimum for text
- **Layout**: Clean alignment, proper whitespace, logical information hierarchy
- **Components**: Consistent button styles, form elements, interactive states
- **Images**: Proper alt text, optimized file sizes, responsive sizing

## Content Approach

- **Headlines**: Clear, benefit-focused, conversion-oriented copy
- **Body Text**: Scannable paragraphs, bullet points for key information
- **CTAs**: Action-oriented, prominent placement, contrasting colors
- **Social Proof**: Testimonials, case studies, client logos when applicable
- **Forms**: Minimal fields, clear labels, inline validation

## Verification Process

After each iteration:
1. Take full-page screenshot at 1440px width
2. Compare side-by-side with reference image
3. Document specific differences in layout, typography, spacing, colors
4. Prioritize fixes by impact (layout > typography > minor spacing)
5. Implement changes and repeat until pixel-perfect

## Business Context

Focus on conversion optimization and professional credibility. This is for mid-market B2B and healthcare clients who need sites that support sales conversations and regulatory compliance. Prioritize clarity over creativity, substance over flash.

## Quality Gate

Site is complete when:
- Visual match is 95%+ accurate to reference
- All responsive breakpoints work properly
- WCAG contrast requirements met
- Forms function correctly
- Loading performance is acceptable
- Code is clean and maintainable