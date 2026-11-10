# Daily Nutrition Tracker

A free, browser-based nutrition and meal-planning app for tracking daily food, nutrients, and water. It is designed around South Indian foods and includes English and Tamil interface options.

**Use the app:** [Open Daily Nutrition Tracker](https://nandhagopal1992.github.io/Nutrition-Tracker/)

## Features

- **Family profiles:** Create separate profiles with a name, age group, age, and weight. Select a profile to track its meals and goals. Activity level can also be adjusted for a profile.
- **Food and meal tracking:** Search and filter the food catalog, enter a serving size in grams, and add foods to the selected date's meal list. Remove individual items or clear that day's list.
- **Daily nutrition progress:** Compare logged intake with estimated daily targets for calories, protein, carbohydrates, calcium, iron, and vitamin C.
- **Meal history calendar:** Review earlier dates, navigate between months, and see which days have meals logged.
- **Water tracking:** Record water in 250 ml or 500 ml increments, adjust the suggested daily goal, and reset the day's count.
- **Nutrition suggestions:** View food recommendations based on nutrients still below the selected profile's goals.
- **Family meal planner:** Generate a suggested balanced menu for a profile, edit its foods and servings, review estimated nutrition coverage, and apply the menu to the rest of the family. Save, reload, update, and delete named meal plans.
- **Family purchase list:** Estimate shopping quantities from saved family menus and review them by daily, weekly, or 30-day monthly periods.
- **Custom recipes:** Build recipes from catalog ingredients, estimate nutrition per 100 g, and save recipes for use in food tracking.
- **English and Tamil:** Choose English, Tamil, or a bilingual display from the language selector.
- **Optional cloud sync:** Sign in with Google when cloud sync is configured and available. Otherwise, the app saves data in the current browser.

Food values use the Indian Food Composition Tables (IFCT) 2017 and USDA FoodData Central where suitable matches are available. Some values are estimates, and some database matches are approximate.

## How to use

1. Open the app in a modern browser.
2. Select a language using the selector at the top of the page.
3. Under **Saved Profiles**, choose **Add Profile**. Enter the person's name, age group, age, and weight, then save. Create a separate profile for each family member.
4. Select the profile you want to track. Set its activity level if needed.
5. In **Add Daily Food**, choose a food type, search for a food, enter the amount in grams, and select **Add**. Repeat for foods eaten that day.
6. Review the progress bars to compare the day's logged nutrients with their estimated goals. Check the nutrition suggestions for ideas to address nutrients that are still below target.
7. Use the **Meal history** calendar to select a different date, review that day's meals, or return to today.
8. Use the water tracker to record drinks and adjust the suggested water goal as appropriate.
9. Open **Family Meal Planner** to create or edit a daily menu. Select a family member, request a suggested menu, and adjust foods or serving amounts. Save plans if you want to reuse them.
10. Open **Family Purchase List** to estimate shopping quantities from the saved menus. Choose daily, weekly, or monthly to review the corresponding amounts.
11. Open **Recipe Menu** to create, edit, or delete custom recipes. Add recipes to the daily food list just like other foods.

## Saving and syncing data

When signed out, profiles, meal history, water intake, recipes, and saved meal plans are stored in the browser's local storage. This data is specific to that browser and device; clearing browser site data or switching devices may remove or leave it behind.

If Google sign-in and Firebase cloud sync are configured for the app, you can sign in to sync supported data with your account. Check the cloud sync status shown near the sign-in controls. Do not rely on cloud sync until the app reports that it is connected.

## Nutrition note

Nutrition targets, food values, portions, water goals, and meal recommendations are estimates for general tracking and planning. They are not medical advice or a substitute for advice from a qualified healthcare professional. Individual needs vary, especially for children and people with medical conditions.

## Technology

The app is a single-page HTML file with its JavaScript and styles included in [index.html](./index.html). It is published using GitHub Pages and does not require a build step or package installation. The page loads some presentation resources from external CDNs, so an internet connection is recommended.

## License

This project is distributed under the [MIT License](./LICENSE).
