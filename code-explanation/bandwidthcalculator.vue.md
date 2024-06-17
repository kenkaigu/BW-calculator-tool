# BandwidthCalculator.vue

1. **Main Container (`#calc`):**
   * The main container for the bandwidth calculator interface.
2. **Title Section:**
   * Displays the title and a note indicating the service is under development.
3. **Subtitle Section:**
   * Shows a subtitle description.
4. **Components:**
   * **Estimated Bandwidth:** A component to estimate bandwidth.
   * **Scope Picker:** A component for selecting the scope.
   * **Object Type Picker:** Displays if a scope is selected.
   * **Number of Users Picker:** Displays if an object type is selected.
   * **Traffic Profile Picker:** Displays if an object type is selected.
   * **Calculation Mode:** Displays if an object type is selected.
   * **Services List:** Displays if an object type is selected.

**Script:**

1. **Imports:**
   * Imports required components and Vuex helper functions.
2. **Component Definition:**
   * Registers imported components.
3. **Data:**
   * Defines `objectTypes` and `servicesList` to store related data.
4. **Computed Properties:**
   * Retrieves objects based on the selected scope from the initial data.
5. **Methods:**
   * Initializes data using Vuex actions.
6. **Lifecycle Hook:**
   * Calls `init` to initialize data when the component is created.
