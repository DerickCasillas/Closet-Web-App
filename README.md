# Closet Database Overview (Updated)

The Closet Database is a structured system designed to help you organize, track, and manage your wardrobe. It functions as a digital catalog of your clothing and accessories, enabling easy access to detailed information about each item. The database can serve various purposes, such as inventory tracking, outfit planning, budgeting, and more.

---

# Key Features (Updated)
1. Categorization:  
   - Items are grouped by category (e.g., tops, bottoms, outerwear, accessories, footwear) for efficient organization.

2. Item Attributes:  
   Each clothing item is described using attributes, such as:
   - Category: The type of clothing or accessory (e.g., shirt, pants, jacket).
   - Color: Primary color of the item.
   - Material: Fabric or material type (e.g., cotton, polyester, leather).
   - Brand: Manufacturer or designer of the item.
   - Size: The size of the item (e.g., Small, Medium, 32W).
   - Condition: Current state of the item (e.g., new, gently used, worn).
   - Date Acquired: When the item was purchased or received.
   - Cost: Purchase price or estimated value.
   - Photo Filename: The filename of an image associated with the item (e.g., `shirt_black.jpg`).
   - Location: Where the item is stored (e.g., closet, drawer, storage box).

3. Search and Filter:  
   - Quickly search for items based on attributes like color, size, or category.
   - Filter items to create lists (e.g., “All black shirts” or “Winter outerwear”).

4. Budget Tracking:  
   - Keep track of spending on clothing and monitor trends over time.

5. Outfit Planning (Optional):  
   - Link items to create pre-planned outfits or style ideas.

---

# Benefits
1. Organization: Provides a centralized location to manage your wardrobe inventory.
2. Convenience: Simplifies finding and selecting clothing items.
3. Budget Awareness: Tracks expenses related to clothing and accessories.
4. Sustainability: Helps identify overused or underutilized items, promoting mindful purchasing and usage.

---

# Technical Notes
1. Photo Storage:
   - The database will store only the filename of each image (e.g., `jacket_blue.jpg`).
   - Images should be kept in a dedicated folder (e.g., `images/`) for easy retrieval.

2. Example File Structure:
   ```
   project/
   ├── main.py
   ├── clothing.db
   ├── images/
       ├── shirt_black.jpg
       ├── jacket_blue.jpg
       ├── shoes_red.jpg
   ```

3. Query Updates:  
   - Ensure image display logic prepends the folder path when needed (e.g., `"images/" + photo_filename`).
