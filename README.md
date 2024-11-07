# Flutter Animation Showcase

This project demonstrates various Flutter animations, including implicit and explicit animations, page route animations, and custom UI interactions. Each animation is illustrated with a unique GIF for better visualization.

## Animations Included

1. **Splash Animation with Page Route Transition**  
   Tap the blue circle to trigger a scale animation, and once complete, it navigates to a new page with a fade transition.
   ![Splash Animation](assets/splash_animation.gif)

2. **Pulsating Circle Animation**  
   A pulsing circular animation created using `TweenAnimationBuilder`, which smoothly scales up and down to simulate a pulsating effect.
   ![Pulsating Circle Animation](assets/pulsating_circle_animation.gif)

3. **Shopping Cart Button Expansion**  
   Tap the cart icon to expand the button, showing an "Added to Cart" message with a check icon, animated using `AnimatedContainer` and `AnimatedOpacity`.
   ![Shopping Cart Button Animation](assets/shopping_cart_animation.gif)

4. **Color Palette Animation**  
   Generates a random color palette with each button press, with smooth transitions between colors using `AnimatedContainer`.
   ![Color Palette Animation](assets/color_palette_animation.gif)

## Code Examples

### 1. Splash Animation with Fade Transition

This animation uses an `AnimationController` to create a scaling effect and triggers a page transition with a fade animation.

```dart
// SplashAnimation widget code here...
