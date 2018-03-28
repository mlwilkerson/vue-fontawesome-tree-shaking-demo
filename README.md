# Demo
This is just a quick demo of the tree-shaking that Just Works for @fortawesome/vue-fontawesome in Font Awesome 5.1.

# Usage
1. `yarn` or `npm install`
1. `yarn build` or `npm run build`
1. `yarn serve` or `npm run serve` and point your browser at http://localhost:4200 to see the coffee icon. It's there.
1. Search the resulting `dist/js/app.*.js` bundle file for icon unicode points to see what's there and what's not.

You should see that code `f0f4` is there, since that the code for `faCoffee`. But you won't see `f007`, the code
for `faUser`.
