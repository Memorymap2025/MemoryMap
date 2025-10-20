# 🎨 Memory Map Customization Guide

## Quick Setup for New Clients

### 1. **Change the Password** (Line 93)
```javascript
const CORRECT_PASSWORD = "1709"; // Change this to your client's password
```

### 2. **Update Title & Subtitle** (Lines 96-97)
```javascript
const CUSTOM_TITLE = "Memory Map"; // Change to client's title
const CUSTOM_SUBTITLE = "A beautiful journey through your most precious memories"; // Change subtitle
```

### 3. **Add Client's Memories** (Lines 100-130)
For each memory, add this format:
```javascript
{
  coords: [34.66, 33.01], // [latitude, longitude] - get from Google Maps
  title: 'Memory Title',
  description: 'Beautiful description of the memory',
  date: '2023-06-15', // Optional: format YYYY-MM-DD
  imgs: ['photos/photo1.jpg', 'photos/photo2.jpg'] // Client's photo filenames
}
```

## 📍 How to Get Coordinates

1. Go to [Google Maps](https://maps.google.com)
2. Find the location
3. Right-click on the exact spot
4. Click the coordinates that appear
5. Copy the numbers (e.g., 34.66, 33.01)

## 📸 Photo Setup

1. Create a `photos` folder
2. Add client's photos to the folder
3. Update the `imgs` array with exact filenames
4. Supported formats: .jpg, .jpeg, .png, .gif

## 🎨 Visual Customization Options

### Change Colors (Optional)
- **Gradient**: Lines 8-9 (background gradient)
- **Button Color**: Line 67 (unlock button)
- **Accent Colors**: Throughout the CSS

### Change Floating Elements (Line 85)
Replace the emojis with different ones:
```javascript
<div class="floating-element" style="left: 10%; animation-delay: 0s;">📸</div>
```

## 📱 Mobile Optimization
The template is already mobile-responsive, but you can adjust:
- Font sizes in the `@media` section (lines 200+)
- Map height on mobile devices

## 🚀 Quick Client Setup Process

1. **Collect from Client:**
   - Photos (high quality preferred)
   - Location names/addresses
   - Memory descriptions
   - Desired password
   - Custom title (optional)

2. **Your Work:**
   - Get coordinates for each location
   - Resize/optimize photos if needed
   - Update the template
   - Test the final result

3. **Delivery:**
   - Send the HTML file + photos folder
   - Or host it online for them

## 💰 Pricing Suggestions

- **Basic Package**: $50-100
  - Up to 10 memories
  - Basic customization
  - 1 revision

- **Premium Package**: $150-300
  - Unlimited memories
  - Full customization
  - Multiple revisions
  - Priority support

- **Luxury Package**: $300-500
  - Everything above
  - Custom design elements
  - Video integration
  - Rush delivery

## 🎯 Marketing Tips

- Create sample maps for different occasions
- Show before/after examples
- Offer seasonal packages (holidays, anniversaries)
- Partner with photographers, event planners
- Create social media content showing your work
