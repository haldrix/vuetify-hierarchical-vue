# vuetify-hierarchical-vue
Proof of concept. UIX to represent the life of a customer in the company, from his arrival in the database, until the finalization of his application for funding. Steps visualized as a hierarchical tree. Each thumbnail can be enriched with more complex features if needed.

## hierarchical view (Customer life cycle)
All the steps are represented and followable by profession. Since the arrival of the contact via Internet or other source, it passes in the various departments of the company, from the salesman to the accounting department. Each user profile has a specific workflow that ends where another one begins. We can visualize the work carried out by each of the services of the company that has been in contact with the customer or has performed actions on his client file.
![Hierarchical view](https://raw.githubusercontent.com/haldrix/vuetify-hierarchical-vue/master/hierarchical-view2.gif)

## Dynamic Thumbnail 1
Depending on the current step, the widgets are more or less complex and have additional features. To avoid overloading the interface too much (which is already the case) these widgets can unfold their contents if necessary. 
Yes, the unfolding animation is less fluid on the gif than in reality 😉.
![Thumbnail 1](https://raw.githubusercontent.com/haldrix/vuetify-hierarchical-vue/master/dynamic_thumbnails.gif)

## Dynamic Thumbnail 2
![Thumbnail 2](https://raw.githubusercontent.com/haldrix/vuetify-hierarchical-vue/master/dynamic_thumbnails2.gif)

