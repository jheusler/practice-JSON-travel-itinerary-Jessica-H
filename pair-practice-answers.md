# Pair Practice: JSON Travel Itinerary

## Nesting

I organized the traveler's contact information as a nested object inside the `traveler` object. This keeps the traveler's name and contact details logically grouped instead of spreading related values across the top level, making the data easier to read and maintain.

## Arrays

I used arrays for both `destinations` and `activities` because each field can contain multiple ordered items. This structure makes it easy to add or remove destinations and activities without changing the overall data model.

## Scalability

The structure can be expanded by adding nested `hotel` and `transportation` objects to each destination. A hotel object could include the hotel name, address, check-in date, check-out date, and confirmation number, while transportation could include the mode, cost, departure time, and arrival time.

## Real-World Application

A travel app or API could use this data to display a complete itinerary, organize plans by destination, send activity reminders, calculate travel costs, and exchange trip information between a client application and a server.

## Partner Addition Discussion

The new destination will expand the itinerary without changing its existing structure. Adding a `transportation` object to every destination will improve the model by keeping the travel method and cost connected to the destination where they apply, making the itinerary more useful for scheduling and budgeting.

## Pull Request URL

To be added after the partner repository is provided and the required unmerged pull request is created.
