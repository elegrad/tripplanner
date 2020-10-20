# Trip Planner for Cultural Routes

A trip / route planner, in association with <a href="https://diazoma.gr">Diazoma</a> for the Cultural Routes of Greek perfectures.

Built using <a href="https://github.com/mavoweb/mavo">Mavo.io</a>, <a href="https://github.com/tailwindlabs/tailwindcss">TailwindCSS</a> and <a href="https://github.com/alpinejs/alpine">AlpineJS</a>

The version for <strong>Ancient Theaters of Epirus</strong> cultural route can be found <a href="https://tripplanner.n6.myws.ca/epirus/mavo-planner.html" target="_blank">here</a>.

---

## Concept

The concept of this tiny application is simple. Using Mavo.io we create 3 simple mavo-apps inside a single html file. The first two fetch the data from the Cultural Route repository API. One mavo-app for the Theaters content type and one mavo-app for the Points of Interest content type. Both are using the mv-add action to add the selected items to the third mavo-app. The third mavo-app is using local storage to create a list of both Theaters and Points of Interest. The user can change their order, change some settings related to the Google Maps Directions URL parameters and get a link for Google Map directions for the whole designed trip, starting from the user's current location.