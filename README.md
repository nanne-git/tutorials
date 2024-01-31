# The Root Route

The first route is what we often call the **_root route_** since the rest of our routes will render inside of it. It will serve as the root layout of the UI, we'll have nested layouts as we get farther along.

# Handling Not Found Errors

Anytime your app throws an error while rendering, loading data, or performing data mutations, React Router will catch it and render an error screen.

**_useRouteError_** provides the error that was thrown. When the user navigates to routes that don't exist you'll get an error response with a "Not Found" **statusText**.
