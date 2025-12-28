# Shadcraft CSS Variables Documentation

## Overview

**Shadcraft** is a Figma UI kit for shadcn/ui that uses **standard shadcn/ui CSS variables**. When exporting themes from Shadcraft or using it with code, it uses the exact same variable structure as shadcn/ui.

This document lists all CSS variables used by Shadcraft/shadcn/ui, showing:
- Variable name
- shadcn/ui default value (zinc theme)
- Shadcraft default value (same as shadcn/ui - using zinc theme)
- Custom values from this project's theme files

**Note on color formats:**
- **OKLCH format**: `oklch(L C H)` (Lightness Chroma Hue) - used in custom themes for better perceptual uniformity

---

## Core Layout Variables

### Border Radius

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--radius` | `0.5rem` (8px) | `0.5rem` (8px) | `0.5rem` (8px) | `0.5rem` (8px) | `0.5rem` (8px) |

---

## Base Neutral Colors

These define the fundamental background and text colors for your application.

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--background` | `oklch(1 0 0)`, `#FFFFFF` | `oklch(1 0 0)`, `#FFFFFF` | `oklch(0.9431 0 0)`, `#ECECEC` | `oklch(0.226 0.013 256.8)`, `#09090B` | `oklch(0.18 0.008 60)`, `#212127` |
| `--foreground` | `oklch(0.172 0.014 265.75)`, `#09090B` | `oklch(0.172 0.014 265.75)`, `#09090B` | `oklch(0.1344 0 0)`, `#080808` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.98 0.003 60)`, `#F9F9FA` |

---

## Card Components

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--card` | `oklch(1 0 0)`, `#FFFFFF` | `oklch(1 0 0)`, `#FFFFFF` | `oklch(0.9824 0.0013 286.38)`, `#F9F9FA` | `oklch(0.226 0.013 256.8)`, `#09090B` | `oklch(0.22 0.008 60)`, `#262629` |
| `--card-foreground` | `oklch(0.172 0.014 265.75)`, `#09090B` | `oklch(0.172 0.014 265.75)`, `#09090B` | `oklch(0.1344 0 0)`, `#080808` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.98 0.003 60)`, `#F9F9FA` |

---

## Popover Components

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--popover` | `oklch(1 0 0)`, `#FFFFFF` | `oklch(1 0 0)`, `#FFFFFF` | `oklch(0.9824 0.0013 286.38)`, `#F9F9FA` | `oklch(0.226 0.013 256.8)`, `#09090B` | `oklch(0.22 0.008 60)`, `#262629` |
| `--popover-foreground` | `oklch(0.172 0.014 265.75)`, `#09090B` | `oklch(0.172 0.014 265.75)`, `#09090B` | `oklch(0.1344 0 0)`, `#080808` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.98 0.003 60)`, `#F9F9FA` |

---

## Primary Interactive Colors

Used for primary buttons, links, and key interactive elements.

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--primary` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.4665 0.1021 162.17)`, `#006B48` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.65 0.18 250)`, `#5B7EFF` |
| `--primary-foreground` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.1326 0.0064 244.3)`, `#06080A` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.18 0.008 60)`, `#212127` |

---

## Secondary Interactive Colors

Used for secondary actions and less prominent interactive elements.

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--secondary` | `oklch(0.961 0.0095 265.75)`, `#F4F4F5` | `oklch(0.961 0.0095 265.75)`, `#F4F4F5` | `oklch(0.9911 0 0)`, `#FCFCFC` | `oklch(0.263 0.009 265.75)`, `#27272A` | `oklch(0.28 0.008 60)`, `#31313A` |
| `--secondary-foreground` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.1326 0.0064 244.3)`, `#06080A` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.9 0.003 60)`, `#E1E1E4` |

---

## Accent Colors

Used for highlighting and drawing attention to specific elements.

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--accent` | `oklch(0.961 0.0095 265.75)`, `#F4F4F5` | `oklch(0.961 0.0095 265.75)`, `#F4F4F5` | `oklch(0.9731 0.0262 159.6)`, `#E8FCF0` | `oklch(0.263 0.009 265.75)`, `#27272A` | `oklch(0.85 0.15 90)`, `#FFDC5E` |
| `--accent-foreground` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.2103 0.0059 285.89)`, `#18181B` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.18 0.008 60)`, `#212127` |

---

## Destructive/Error Colors

Used for destructive actions, errors, and warnings.

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--destructive` | `oklch(0.628 0.257 29.23)`, `#EF4444` | `oklch(0.628 0.257 29.23)`, `#EF4444` | `oklch(0.6416 0.2236 26.24)`, `#F73B3B` | `oklch(0.439 0.182 29.23)`, `#7F1D1D` | `oklch(0.62 0.2 25)`, `#DC2626` |
| `--destructive-foreground` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.1149 0 0)`, `#050505` | `oklch(0.985 0 0)`, `#FAFAFA` | `oklch(0.98 0.003 60)`, `#F9F9FA` |

---

## Muted States

Used for disabled states, placeholder text, and subdued content.

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--muted` | `oklch(0.961 0.0095 265.75)`, `#F4F4F5` | `oklch(0.961 0.0095 265.75)`, `#F4F4F5` | `oklch(0.9642 0 0)`, `#F3F3F3` | `oklch(0.263 0.009 265.75)`, `#27272A` | `oklch(0.28 0.008 60)`, `#31313A` |
| `--muted-foreground` | `oklch(0.5205 0.016 265.75)`, `#71717A` | `oklch(0.5205 0.016 265.75)`, `#71717A` | `oklch(0.3942 0 0)`, `#464646` | `oklch(0.674 0.019 265.75)`, `#A1A1AA` | `oklch(0.6 0.01 60)`, `#8C8C96` |

---

## Borders & Inputs

| Variable | shadcn/ui Default | Shadcraft Default (Light) | Custom Light | Shadcraft Default (Dark) | Custom Dark |
|----------|-------------------|---------------------------|--------------|--------------------------|-------------|
| `--border` | `oklch(0.906 0.015 265.75)`, `#E4E4E7` | `oklch(0.906 0.015 265.75)`, `#E4E4E7` | `oklch(0.8297 0 0)`, `#C7C7C7` | `oklch(0.263 0.009 265.75)`, `#27272A` | `oklch(0.32 0.01 60)`, `#3D3D47` |
| `--input` | `oklch(0.906 0.015 265.75)`, `#E4E4E7` | `oklch(0.906 0.015 265.75)`, `#E4E4E7` | `oklch(0.88 0.005 60)`, `#DCDCE0` | `oklch(0.263 0.009 265.75)`, `#27272A` | `oklch(0.32 0.01 60)`, `#3D3D47` |
| `--ring` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.205 0.012 265.75)`, `#18181B` | `oklch(0.3354 0.072159 163.3242)`, `#00422C` | `oklch(0.848 0.017 265.75)`, `#D4D4D8` | `oklch(0.68 0.13 250)`, `#6B88FF` |

---

## Sidebar Components

Sidebar-specific color variables for navigation components.

| Variable | Custom Light Value | Custom Dark Value |
|----------|--------------------|--------------------|
| `--sidebar` | `oklch(0.995 0.003 60)`, `#FEF8FD` | `oklch(0.18 0.008 60)`, `#212127` |
| `--sidebar-foreground` | `oklch(0.2 0.005 60)`, `#252529` | `oklch(0.9 0.003 60)`, `#E1E1E4` |
| `--sidebar-primary` | `oklch(0.4665 0.1021 162.17)`, `#006B48` | `oklch(0.68 0.13 250)`, `#6B88FF` |
| `--sidebar-primary-foreground` | `oklch(0.99 0 0)`, `#FCFCFC` | `oklch(0.18 0.008 60)`, `#212127` |
| `--sidebar-accent` | `oklch(0.97 0.004 60)`, `#F6F0F5` | `oklch(0.24 0.008 60)`, `#2D2D33` |
| `--sidebar-accent-foreground` | `oklch(0.2103 0.0059 285.89)`, `#18181B` | `oklch(0.9 0.003 60)`, `#E1E1E4` |
| `--sidebar-border` | `oklch(0.8297 0 0)`, `#C7C7C7` | `oklch(0.3 0.01 60)`, `#383842` |
| `--sidebar-ring` | `oklch(0.3354 0.072159 163.3242)`, `#00422C` | `oklch(0.68 0.13 250)`, `#6B88FF` |

---

## Chart Colors

Used for data visualization and charts.

| Variable | Custom Light Value | Custom Dark Value |
|----------|--------------------|--------------------|
| `--chart-1` | `oklch(0.4665 0.1021 162.17)`, `#006B48` | `oklch(0.65 0.18 250)`, `#5B7EFF` |
| `--chart-2` | `oklch(0.7048 0.1918 304.89)`, `#BC7BFE` | `oklch(0.7 0.2 35)`, `#FF9263` |
| `--chart-3` | `oklch(0.8165 0.1098 233.62)`, `#75CFFF` | `oklch(0.65 0.18 245)`, `#5278FF` |
| `--chart-4` | `oklch(0.9104 0.1726 98.68)`, `#FFE23D` | `oklch(0.78 0.16 75)`, `#FFBD47` |
| `--chart-5` | `oklch(0.7039 0.1915 37.13)`, `#FF6A3D` | `oklch(0.65 0.21 20)`, `#FF5733` |

---

## Extended Custom Variables

These are custom variables added to the project beyond the standard shadcn/ui set.

### Status Colors

| Variable | Purpose | Light Value | Dark Value |
|----------|---------|-------------|------------|
| `--success` | Success states | `oklch(0.9009 0.1007 157.22)`, `#A5F3C4` | `oklch(0.67 0.15 155)`, `#20C997` |
| `--success-foreground` | Success text | `oklch(0.1149 0 0)`, `#050505` | `oklch(0.18 0.008 60)`, `#212127` |
| `--info` | Info states | `oklch(0.8165 0.1098 233.62)`, `#75CFFF` | `oklch(0.65 0.18 245)`, `#5278FF` |
| `--info-foreground` | Info text | `oklch(0.1149 0 0)`, `#050505` | `oklch(0.18 0.008 60)`, `#212127` |
| `--warning` | Warning states | `oklch(0.9104 0.1726 98.68)`, `#FFE23D` | `oklch(0.78 0.16 75)`, `#FFBD47` |
| `--warning-foreground` | Warning text | `oklch(0.1149 0 0)`, `#050505` | `oklch(0.18 0.008 60)`, `#212127` |
| `--error` | Error states | `oklch(0.7039 0.1915 37.13)`, `#FF6A3D` | `oklch(0.65 0.21 20)`, `#FF5733` |
| `--error-foreground` | Error text | `oklch(0.1149 0 0)`, `#050505` | `oklch(0.98 0.003 60)`, `#F9F9FA` |

### Additional Interactive Colors

| Variable | Purpose | Light Value | Dark Value |
|----------|---------|-------------|------------|
| `--secondary-accent` | Secondary accent color | `oklch(0.7048 0.1918 304.89)`, `#BC7BFE` | `oklch(0.7 0.2 35)`, `#FF9263` |
| `--secondary-accent-foreground` | Secondary accent text | `oklch(0.1149 0 0)`, `#050505` | `oklch(0.18 0.008 60)`, `#212127` |

### Custom Muted Variants

| Variable | Purpose | Light Value | Dark Value |
|----------|---------|-------------|------------|
| `--primary-muted` | Muted primary (hover states) | `oklch(0.9829 0.024 167.12)`, `#EBFFF6` | `oklch(0.24 0.05 250)`, `#2E2E5B` |
| `--secondary-OnContainer` | Secondary on container | `oklch(0.9431 0 0)`, `#ECECEC` | `oklch(0.28 0.008 60)`, `#31313A` |

### Gradient Colors

| Variable | Purpose | Light Value | Dark Value |
|----------|---------|-------------|------------|
| `--gradient-yellow` | Gradient yellow | `oklch(0.82 0.14 95)`, `#FFC847` | `oklch(0.82 0.14 95)`, `#FFC847` |
| `--gradient-blue` | Gradient blue | `oklch(0.7389 0.1481 241.96)`, `#5C96FF` | `oklch(0.65 0.13 245)`, `#5278FF` |
| `--gradient-purple` | Gradient purple | `oklch(0.894 0.0667 307.63)`, `#E4C5FF` | - |
| `--gradient-red` | Gradient red | `oklch(0.6662 0.2237 35.33)`, `#FF6A3D` | `oklch(0.65 0.19 30)`, `#FF5733` |
| `--gradient-green` | Gradient green | `oklch(0.4665 0.102061 162.1699)`, `#006B48` | `oklch(0.68 0.13 160)`, `#1FD995` |

### Hero Components

| Variable | Purpose | Light Value | Dark Value |
|----------|---------|-------------|------------|
| `--hero-background` | Hero section background | `linear-gradient(90deg, oklch(0.3354 0.072159 163.3242), oklch(0.4665 0.102061 162.1699))` | `linear-gradient(90deg, oklch(0.55 0.15 250), oklch(0.68 0.13 160))` |
| `--hero-foreground` | Hero section text | `oklch(0.99 0 0)`, `#FCFCFC` | `oklch(0.98 0.003 60)`, `#F9F9FA` |

### Navbar

| Variable | Purpose | Value |
|----------|---------|-------|
| `--navbar-accent-opacity` | Navbar accent opacity | `0.45` |
| `--navbar-accent-gradient` | Navbar accent gradient | Complex gradient (see theme files) |
| `--navbar-accent-filter` | Navbar accent blur | `blur(40px)` |

### Typography

| Variable | Purpose | Value |
|----------|---------|-------|
| `--text-accent` | Monospace font family | `'Roboto Mono','Consolas', 'Menlo', 'Monaco', monospace` |

---

## Usage Notes

### Shadcraft & shadcn/ui Compatibility

1. **Shadcraft uses identical variable names to shadcn/ui** - there is no separate variable structure
2. **Color format**: Both use OKLCH color space for better color manipulation and perceptual uniformity
3. **Dark mode**: Implemented via `.dark` class selector
4. **Component compatibility**: Variables work seamlessly with both Shadcraft Figma components and shadcn/ui React components

### Implementation

To use these variables in your project:

1. **Import the theme file** in your `globals.css` or main CSS file:
   ```css
   @import './shadcraft-theme-light.css';
   @import './shadcraft-theme-dark.css';
   ```

2. **Configure Tailwind CSS** to use CSS variables in `tailwind.config.js`:
   ```js
   module.exports = {
     theme: {
       extend: {
         colors: {
           background: 'hsl(var(--background))',
           foreground: 'hsl(var(--foreground))',
           // ... other variables
         }
       }
     }
   }
   ```

3. **Use in components** via Tailwind utilities:
   ```jsx
   <div className="bg-background text-foreground">
     <button className="bg-primary text-primary-foreground">
       Click me
     </button>
   </div>
   ```

### Color Space: OKLCH

OKLCH (Oklab Lightness Chroma Hue) provides:
- **Perceptual uniformity**: Colors appear equally bright at the same lightness value
- **Better interpolation**: Smooth gradients and color transitions
- **Wide color gamut**: Access to more vibrant colors
- **Format**: `oklch(L C H)` where L = lightness (0-1), C = chroma (0-0.4), H = hue (0-360)

---

## File Structure

```
/Users/jefflerch/Documents/Github/CS-Shad-variables/
├── theme-light.css              # Original shadcn theme (light)
├── theme-dark.css               # Original shadcn theme (dark)
├── shadcraft-theme-light.css    # Shadcraft-compatible theme (light)
├── shadcraft-theme-dark.css     # Shadcraft-compatible theme (dark)
└── SHADCRAFT-VARIABLES.md       # This documentation
```

---

## Resources

- **shadcn/ui Theming Docs**: https://ui.shadcn.com/docs/theming
- **Shadcraft Official Site**: https://shadcraft.com/
- **Shadcraft Documentation**: https://shadcraft.com/docs
- **Shadcraft Variables Guide**: https://shadcraft.com/docs/variables
- **OKLCH Color Picker**: https://oklch.com/

---

*Last updated: December 2024*
