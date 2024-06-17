# ServiceCard.vue

* **Card Display:**
  * Shows a service card with dynamic classes based on the service's state (disabled or error).
* **Title Section:**
  * Includes a checkbox for toggling the service's active state (visible in extended mode) and displays the service name.
* **Extra Information:**
  * Displays service bandwidth and a popover with additional service details on hover.
* **Basic Information:**
  * Shows basic details like transfer rate, delay, intensity per user, and session data (visible when advanced mode is off).
* **Advanced Information:**
  * Provides editable fields for advanced settings, only accessible when advanced mode is on and the service is active.
* **Methods:**
  * Update service properties and force component updates on input changes.
  * Toggle the service's active state and recalculate active services.
* **Computed Properties:**
  * Determine the visibility of extended and advanced modes based on settings.
  * Apply appropriate classes for error and disabled states.
