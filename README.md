# flutter_provider

A simple Flutter application built with provider architecture.

Enhanced to avoid redundant widget builds triggered by Provider. E.g. When the provider has a List property, updates to individual items of the list should trigger updates to the corresponding UI elements only. We demonstrate that here by using nested ChangeNotifiers in the model.

