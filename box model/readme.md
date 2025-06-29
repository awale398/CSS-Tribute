🧠 Box Model Concepts (Explained in My Own Words)
### ✅ box-sizing: border-box
This tells the browser to include the padding and border inside the element’s total width and height. That means if a card is 300px wide and has padding: 20px and border: 5px, the content will only take up the remaining space. Without this, the box would grow unexpectedly.

✅ padding
Padding is the space inside the box between the content and the border. It pushes the content inward. For example, padding: 20px; makes sure the text and image don’t touch the edges of the card.

✅ border
Border wraps the padding and content. It’s like the visible “frame” of the element. In this project, we used border: 5px solid #3498db; to create a strong blue frame around each card.

✅ margin
Margin is the space outside the box. It pushes the entire box away from other boxes. We used margin: 10px; to separate cards from each other and prevent overlap.

✅ width
This controls how wide the card is. We set width: 300px; to give each card a consistent size.

🎨 Style & Layout Properties
✅ display: flex + justify-content: space-around
This allows the .card-container to arrange its children (.card) in a row. space-around evenly spaces out the cards.

✅ flex-wrap: wrap
Ensures the cards move to the next row if the screen is too narrow — making it responsive.

✅ gap: 20px
Creates even spacing between the cards inside the flex container.

🖼️ Visual Styling
✅ border-radius
Smooths the corners of the card and image. border-radius: 10px; makes it look modern and clean.

✅ box-shadow
Adds depth by casting a soft shadow around the card:
box-shadow: 0 4px 10px rgba(0,0,0,0.1); gives a floating effect.

✅ transition + transform: scale(1.03)
When you hover over a card, it slightly grows — this is a hover animation that makes the UI feel interactive.

📱 Responsive Considerations
✅ flex-wrap: wrap + width: 300px
Instead of shrinking cards on smaller screens, the layout wraps them to new lines. This keeps the design neat and readable.