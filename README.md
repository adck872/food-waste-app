# food-waste-app

# Login page:

logo at top,
text box at bottom for username and password,
submit button at bottom
registration link if not registered

# Registration page (linked from login page):

logo at top,
text box for first name
text box for last name
text box for username
text box for password

submit button at bottom
login page link at bottom

# Home page (Dashboard):

welcome message at top "welcome name"
top bar navigation bar - logo, notification icon, settings icon
bottom bar navigation bar- icons for key pages: pantry, recipes, waste stats, rewards, composting, environmental tips

Quick stats:
Show a summary of pantry status:
Items expiring soon: “5 items expiring this week!”
Most-wasted item: “You’ve wasted 2 potatoes this month.”
Include a button: “View Pantry”.

Quick Actions
Horizontal row of buttons with icons:
Add Item (➕)
Scan Barcode (📷)
Find Recipes (🍴)

Waste Stats
Mini-bar chart: Wasted vs. Used this week.
Progress bar for reducing waste.
Button: “View Stats.”

Sustainability Tip
🌱 “Did you know? Composting reduces food waste by 30%!”
Button: “More Tips.”

Rewards Progress
Progress bar: 60% toward next badge.
Button: “View Rewards.”

# Pantry page (linked from bottom nav bar)

Filter/Sort Button:
A button to open a filter/sort menu for:
Sorting items by Name, Expiration Date, or Category.
Filtering to show only items that are Expiring Soon or Recently Added.

Viewing Items:

If the pantry is empty, display an informative and engaging empty state:

Illustration: A cute empty basket or fridge illustration.
Message: "Your pantry is empty! Add your first item to get started."
Call to Action: A button saying “Add Item” to encourage users to populate their pantry

User opens the pantry and sees a list of categorized items (e.g., Milk under Dairy).
Notices an expiration warning on Bread (Expires Tomorrow in red).

Individual Items: Each item is displayed as a row /card with the following details:

Item Name: Bold (e.g., Milk).
Quantity: Displayed next to the name (e.g., 2 Bottles).
Expiration Date: A small label below the item name (e.g., Expires in 3 Days). Items expiring soon can have the label in red.
A small edit (✏️) and delete (🗑️) button on each row.

A large, floating “+ Add Item” button in the bottom right corner of the screen:
Tapping this button opens the Add Item Modal/Page.
The button should be vibrant

Place a small barcode scanner button next to the Add Item button.
Tapping it opens the phone’s camera to scan a barcode and populate the item details automatically.
If the user clicks "Scan Barcode" instead of manually adding an item:

Open the phone’s camera view for barcode scanning.
After scanning, fetch data (item name, category, etc.) from a database or API.
Populate the fields automatically in the “Add Item” form.
User confirms the details and saves the item.

Frequently Used Items Section:

A collapsible section at the top that lists frequently added items (e.g., Eggs, Milk, Bread).
Allows users to quickly re-add common items.

# add item form layout (link from pantry page + item)

Header:
Title: "Add a New Item".
Cancel Button (top-left): Allows users to discard changes and return to the pantry page.
Save Button (top-right): Saves the item and updates the pantry.

Form Fields:
Item Name:

Input field with a placeholder: "e.g., Milk, Bread, Apples".
Validation: Ensure the field isn’t left empty.
Category (Dropdown or Auto-Suggestion):

Options like Produce, Dairy, Meat, Grains, Snacks, etc.
Let users type or select pre-defined categories for quick input.
Quantity:

Number input or +/- buttons to set the quantity (e.g., 2 Bottles).
Expiration Date:

A date picker for selecting when the item will expire.
Optional quick shortcuts like:
"Expires in 3 Days"
"Expires Next Week"

Quick Add (Optional Feature):
Include a “Quick Add” button in the form.
Pre-fill fields based on frequently added items or templates (e.g., “Milk, 1 Bottle, 7 Days”).

# recipe page - tailored to their pantry inventory and personalized recommendations with search options and filtering capabilities

Title Recipes at the top of the tape
search bar to search recipes by name, ingredient, cuisine, dietry preferences, cooking timeso etc
high priority recipe recommendations (expiring ingredients)
section which is a horizontal scrollable row at the top that says dont waste these ingredients

a vertical scrollable list of recipe cards where each card has
recipe image, title key info like prep and cook time and ingredients matched from your pantry action buttons view recipe to open full details, save to favourites. add a clickable heart icon in the corner of each recipe card to favourite/unfavourite

Substituted recipes section - using alternative ingredients when pantry missing certain key items

- recipes that wouldve matched expiring ingredients but substitute for missing ones ( if out of eggs use yoghurt)
  cards for each recipe but with a substitution
  save or favourite recipe. add a clickable heart icon in the corner of each recipe card to favourite/unfavourite

favourite button at the top of the page "View all favourites" take to favourites tab on the same page to favourite section

# waste page - user insights about their food-saving habits, waste patterns and overall contribution toward reducing food waste

Title Waste statistics in centre
include a tage line or stat such as " you saved this much food this month"
filter or drop down for time periods (weekly,monthly,yearly)

summary card section - showing key stats or horizontal scrollable area
total food saved in weight
total waste reduced in waste in percentage or volume
environmenta impact : equivalent co2 emmisions saved

graph of their waste trends over the past month
line graph/barchart to track food waste over time

breakfown of waste by category in a pie chart underneath graph of their waste trends

- notice vegetable category high add a tip below chart recommends proper storage methods etc
  food waste vs food saved chart

comparison graph : to compare user stats to their past performance

# Environmental tips page - provides personalized tips and educational content to reduce food waste

Header at top title "Environmental tips"
"small actions, big impact" subtitle underneath
Content:brief introduction about the environmental consequences of food waste, providing statistics how much food gets wasted globally and the environmental toll it takes

Personalized Tips Based on User Behavior
Header: "Your Personalized Tips"
Content: Based on the user’s pantry inventory and food consumption history, show tailored tips or suggestions. For example, if they frequently waste fruits, give them tips on storing them better or using them in smoothies.
Example:

“You often waste bananas. Try freezing them for smoothies or baking banana bread!”

Tips section present in cards or a list with icons to each tip
Example of Tips:

Plan Your Meals: “Planning meals in advance helps you buy only what you need, reducing impulse buys that often end up in the trash.” [Image/Icon of a meal planner or calendar]

Store Properly: “Proper storage extends the shelf life of your food. Learn the best ways to store fruits, vegetables, dairy, and more.” [Image/Icon of food storage]

Use Leftovers Creatively: “Transform yesterday’s dinner into a new meal! From soups to smoothies, leftovers can become your next meal.” [Image/Icon of leftovers in a container]

Check Expiration Dates: “Before buying new food, check the expiration dates and use what’s close to expiring first.” [Image/Icon of an expiration date]

Buy in Smaller Quantities: “Buy only what you’ll use in a week to prevent spoilage and unnecessary waste.” [Image/Icon of a shopping list or smaller portions]
