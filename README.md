# Next.js 15 App Router: Unexpected Behavior with Simple Function Component

This repository demonstrates an unexpected behavior encountered when using a simple function component in the `pages` directory of a Next.js 15 application using the App Router.

## Issue

The issue is that a basic function component, such as the one shown below, in the `pages` directory does not render properly in Next.js 15 with the App Router enabled.

## Reproduction

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Start the development server using `npm run dev`.
4. Observe that the page does not render as expected.

## Solution

The solution is to move the component into the `app` directory or to modify its structure to be compatible with the App Router.

See the `bugSolution.js` file for a corrected implementation.