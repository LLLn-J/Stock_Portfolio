Create new portfolio interface called EnhancedPortfolio to support new features, and remain the original Portfolio unchanged.
implement the new features in the EnhancedPortfolio class, and ensure that the original Portfolio class remains unchanged.



Our program is structured based on the standard Model-View-Controller (MVC) architecture, which facilitates clear separation of concerns and enhances maintainability.

Components:

- Model:
  - Stock: Manages stock-related data and operations.
  - Portfolio: Handles the aggregation of stocks and calculation of portfolio values.
  - User: Represents user data and interactions within the system.
  - Main Model: Acts as the central unit connecting the Controller and View components, ensuring seamless data flow and interaction handling.

- Controller:
  - Manages the input from users and translates it into actions for the Model or updates to the View.

- View:
  - Handles all output representations to the user, ensuring that the user interface is separated from the data processing.

- Main Program:
  - Located under the 'src' directory, it serves as the executable entry point, integrating all three MVC components to drive the application.