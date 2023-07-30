# &Retour Technical Documentation
## Introduction
&Retour is a browser extension to give more insightful information about your daily commute and travels.

![etRetourDemo](https://github.com/GitXenon/et-retour/assets/46031014/21b27a46-259e-4fa9-acc3-719e07b0f57a)

The destination card is automatically enriched with estimates for the costs and the carbon emissions by the application.
<table>
  <tr>
    <th>Before</th>
    <th>After</th>
  </tr>
  <tr>
    <td>
      <img width="300" alt="Before" src="https://github.com/GitXenon/et-retour/assets/46031014/62d75972-ab04-400e-b31a-076cec300cc4">
    </td>
    <td>
      <img width="302" alt="After" src="https://github.com/GitXenon/et-retour/assets/46031014/a561944c-fb11-4d6a-b058-469fa8b788c8">
    </td>
  </tr>
</table>

## Frontend
The Frontend is written using TypeScript, Tailwind CSS and Webpack.

## Backend
The Backend is written in Go with a MySQL database.

## Testing
We use end-to-end testing for the frontend app using Playwright.
