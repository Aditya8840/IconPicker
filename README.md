# Icon Picker Component

## Description

This project is a React component for selecting icons. The Icon Picker component displays a grid of icons, allowing users to paginate through them and select one. The selected icon is then displayed in a designated area.

## Features

- Displays a grid of icons.
- Paginated view for navigating through a large set of icons.
- Customizable properties such as the number of rows, columns, icon dimensions, and picker dimensions.
- Clickable icons that update the main display with the selected icon.
- Modal popup for the icon picker that can be closed.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aditya8840/IconPicker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd icon-picker-component
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the application:
    ```bash
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`.

3. Click on the main icon display area to open the icon picker modal.

4. Select an icon from the modal. The selected icon will be displayed in the main area.

## Customization

The `Iconmodel` component accepts several props for customization:

- `rowsInOnePage` (Number): The number of rows in one page of the icon grid.
- `columnsInOnePage` (Number): The number of columns in one page of the icon grid.
- `iconHeight` (Number): The height of each icon.
- `iconWidth` (Number): The width of each icon.
- `pickerHeight` (String): The height of the icon picker modal. Default is `500px`.
- `pickerWidth` (String): The width of the icon picker modal. Default is `500px`.
- `onIconSelect` (Function): The callback function when an icon is selected.
- `onClose` (Function): The callback function to close the icon picker modal.