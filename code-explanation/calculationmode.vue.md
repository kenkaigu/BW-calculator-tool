# CalculationMode.vue

1. **Container (`.calculation-mode-picker`):**
   * The main container for the calculation mode picker interface.
2. **Title:**
   * Displays a title for the calculation mode picker.
3. **Radio Group:**
   * A group of radio buttons for selecting the calculation mode.
   * Each radio button represents a different calculation mode (Simple, Extended, Advanced).

**Script:**

1. **Imports:**
   * Imports Vuex helper function `mapGetters`.
2. **Component Definition:**
   * Defines the component name and data properties.
3. **Data:**
   * Holds the currently selected mode (default is 'SIMPLE').
   * An array of calculation modes with their names and keys.
4. **Computed Properties:**
   * Retrieves selected settings from the Vuex store.
5. **Lifecycle Hooks:**
   * Adds an event listener for 'clearSettings' when the component is mounted.
   * Removes the 'clearSettings' event listener before the component is destroyed.
6. **Methods:**
   * Commits the selected calculation mode to the Vuex store when a radio button is changed.
   * Resets the calculation mode to 'SIMPLE' and commits the change to the Vuex store when the 'clearSettings' event is triggered.
