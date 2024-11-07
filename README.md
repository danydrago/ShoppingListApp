# Shopping List App - README

## Overview
This is a simple Android app designed to help users create and manage a shopping list. The app allows users to add items to a list, specifying both the name and quantity of each item. Users can also edit or delete items in the list. 

Currently, all data is stored temporarily in memory. This means that the list will be cleared each time the app is closed or restarted. This app provides a straightforward solution for creating quick, disposable shopping lists.

## Features
- **Add items**: Users can add items to the shopping list by entering the name and quantity.
- **Edit items**: Users can edit the name or quantity of existing items.
- **Delete items**: Users can remove items from the list if they are no longer needed.
- **Temporary storage**: The list is stored in memory and will reset when the app is closed.

## Getting Started

### Prerequisites
- Android Studio installed on your development machine.
- Android device or emulator running Android 14 or later.

### Installation
1. Clone the repository   
2. Open the project in **Android Studio**.
3. Build and run the app on your Android device or emulator.

## How to Use
1. **Add an item**: Tap on the "Add Item" button and enter the item name and quantity.
2. **Edit an item**: Tap on an item in the list to open an edit dialog where you can update the name and/or quantity.
3. **Delete an item**: Long press an item to delete it from the list.
4. **Exit the app**: Closing the app will delete all items in the list, as it is stored temporarily in memory.

## Future Improvements
- Implement persistent storage (e.g., SQLite, Shared Preferences) so that the list can be saved even when the app is closed.
- Add categories for different types of items (e.g., groceries, electronics).
- Allow users to mark items as "purchased" or "completed."
- Enable sorting and filtering options.

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request. We welcome bug fixes, feature requests, and any other contributions!

## License
This project is licensed under the MIT License.

---

Thank you for using the Shopping List App!
