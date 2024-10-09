---
title: UI Design Flaws and Fixes for Google Maps
layout: doc
---

# UI Design Tradeoffs for Google Maps

In class, we talked about the safety and usability implications of the design of Tesla center console interfaces. We considered how on one hand, the interface is useful for passengers, as it might be more intuitive as a huge collection of ambiguous buttons. However, on the other hand, by not having physical buttons and having moving and changing components, the interface forces the driver to look away from the road and toward the console in order to accurately interact with it.

Similarly, I wanted to reflect on the safety and usability tradeoffs in the design of Google Maps. Below, you can see a screenshot of Google Maps during route navigation. 

<img src="/images/googleMaps.png" alt="Google Maps Mobile Navigation Interface" style="border-radius: 48px; width: 300px; height: auto;">


One significant flaw in the Google Maps mobile interface is the placement of the reroute and exit buttons. These buttons are positioned close together on the screen, increasing the likelihood of accidentally exiting navigation while attempting to reroute. This can lead to confusion and panic for drivers who lose their navigation guidance while on the road. To address this issue, I propose moving the exit button off the main screen entirely, as it is rarely needed while driving. Instead, we could place it in the menu that appears when users drag upward from the gray bar, ensuring it is still easily accessible, but cannot be clicked accidentally while driving.

Additionally, Google Maps employs a wide color palette and various visual details to convey information about routes, traffic conditions, and points of interest. However, this abundance of colors and details can be distracting for drivers. As we discussed in class, bright colors can draw attention toward the interface and therefore away from the road, forcing drivers to parse and sift through unnecessary information while trying to navigate. To improve this, we could introduce a "driving mode" that greys out the background, minimizing the prominence of landmarks and lawns. In this mode, the route, traffic signs, and the arrow indicating the vehicle's location would remain in bright colors, highlighting the most important elements for navigation.

Finally, another usability concern is that the four buttons on the right of the Google Maps interface are the same size, regardless of their importance or likelihood of use. This uniformity neglects the fact that drivers need to quickly access critical buttons with just a glance at the screen. For instance, the compass button is the same size as the button that reads out navigation information, even though the latter is far more essential while driving. To enhance usability, we should make the most important buttons, such as the one that reads out navigation info, larger and more accessible, while reducing the size of less frequently used buttons.

To conclude, both Tesla's center console and the Google Maps interface highlight the tradeoffs of safety and usability in technology design. Google Maps poses safety risks and reduces practical usability through unfortunate button placement, overwhelming colors, and component sizing. By making some very small thoughtful UI design adjustments, we can improve usability and enhance safety for drivers.

