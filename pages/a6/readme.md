## A6: Emoji Essay

Game-of-life cellular automata

### Analysis

In the real world, the formation (and dissipation) of clouds depends on several meteorological factors, such as drafts, humidity/temperature of surrounding air, and even the terrain of the land below. While these factors by themselves aren't fundamentally complex, taking them all into consideration is what makes simulating clouds and realistic weather challenging. Thus, the behavior of clouds and weather is often simplified to make it close to realism as possible. In this essay, only the most basic phenomena is taken into consideration: the water cycle.

Fundamentally, the water cycle rotates between evaporation, condensation, and precipitation. The simulations in this essay attempt to recreate a simple model of this cycle and visualizes it using cloud, rain cloud, and water droplet emojis. The main objective is to observe how adding certain elements of the water cycle affects the behavior of clouds. Specifically, **can clouds remain relatively consistent in size and shape if only the water cycle is involved (and no other meteorological factors)?**

To start off, the "clouds only" simulator was designed to keep the shape and size of clouds consistent. The only stage of the water cycle involved here is evaporation, but this is simply from random probability. From this, rain cloud formation rules (precipitation) were added; whether or not rain clouds formed depended on how dense the clouds were. However, this is still only involving the behavior of clouds with other clouds; what about clouds interacting with the terrain below? Thus, the third simulation allows for rain clouds to leave the ground wet, and wet grounds have an increased chance to evaporate and form clouds (condensation).

Throughout these simulations, as more components of the water cycle were added, clouds were more likely to become increasingly dense and grow in size. By the third simulation, it's not unlikely to end up with a grid full of clouds. Therefore, **with the water cycle alone, clouds cannot remain relatively consistent in size and shape.** In fact, it's the other meteorlogical factors that make clouds and storms dissipate without the need for precipitation.
