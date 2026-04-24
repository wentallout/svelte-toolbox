# svelte-toolbox

this project should people who work with svelte daily start agentic-coding-ready.

## Things to leave in root +layout.svelte


## Animations and Motions

- [Svelte's Built-in Transition](https://svelte.dev/docs/svelte/svelte-transition)

### Core Animation Libraries

- [svelte-motion](https://svelte-motion.gradientdescent.de/): Port of Framer Motion to Svelte. Honestly pretty slick for hover states and page transitions... can save you from writing a bunch of custom CSS keyframes lol
- [Motion One](https://motion.dev/): Super lightweight (~3KB) animation lib built on Web Animations API. If you just need simple keyframe animations without all the bells and whistles, this is perfect
- [svelte-action-motionone](https://github.com/rootenginear/svelte-action-motionone): Wraps Motion One as a Svelte action. Nice if you prefer the action pattern... keeps your components cleaner too
- [GSAP with Svelte](https://gsap.com/docs/v3/Installation/?checked=core,svelte): The heavyweight champion. Timeline control, ScrollTrigger, morphing - basically everything. Honestly it can be overkill for most projects but when you need that complex scroll animation... nothing else comes close
- [AutoAnimate](https://github.com/formkit/auto-animate): This one's kinda magic - just slap it on a container and it auto-animates layout changes. No more jarring list reorders. Works for Svelte too

### Component Collections

[Svelte Animations](https://github.com/SikandarJODD/svelte-animations): Gallery of copy-paste micro-interactions built with Svelte Motion + Tailwind. Pretty useful when you need something quick and don't want to build from scratch

[Motion Core](https://github.com/Motion-Core/motion-core): A set of Svelte 5 motion components (including animated backgrounds to 3D effects), delivered with a copy-paste architecture instead of heavy dependencies. 

### Scroll & Viewport Detection

- [svelte-inview](https://github.com/svelte-inview/svelte-inview): Simple Intersection Observer action. This could be used for triggering animations on scroll or lazy loading images.
- [animate-on-view](https://github.com/denisetiya/animate-on-view): Zero deps, 40+ entrance animations. Honestly a bit much sometimes but great for landing pages when you need a specific entrance animation lol
- [saos](https://github.com/shiryel/saos): A minimalist "animation on scroll" component powered by Intersection Observer and CSS animations.
- [svelte-scrollto-element](https://github.com/bartholomej/svelte-scrollto-element): Lightweight scroll-to component for smooth scrolling back to an element. No deps and works with SSR and SvelteKit.
- [sveltekit-view-transition](https://github.com/paoloricciuti/sveltekit-view-transition): Native View Transitions API for SvelteKit. Still experimental but... the page transitions are buttery smooth

### Animation Formats & Players

- [Rive](https://rive.app/): You can create complex animations with their editor and then export to web. Plus make them interactive also.
- [dotLottie Web](https://github.com/LottieFiles/dotlottie-web): Canvas/WASM renderer for Lottie files. Way smoother than the old Lottie player, especially on mobile


## Credits

https://www.reddit.com/r/sveltejs/comments/1suhono/ultimate_list_of_svelte_animation_and_motion/
