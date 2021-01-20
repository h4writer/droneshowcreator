===========================
Bezier movement
===========================

  *A bezier is a parametric curve that consists of a connection between a starting point and an end point with anchor point. Used to draw straight lines, turns and curves that the drones take as their flight path. Be careful with a formation of drones, the center of the formation will always follow the curve. A design can of course consist of a concatenation of several points, each intermediate point gets 2 anchor points to adjust the curve. Use the three cube icons front view, side view and top view to easily draw your path in depth and all dimensions.*

  .. image:: images/bezier.jpg

  - Properties:

    - Start

      *Shows the time when a action bezier starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Keyframes

      * With a keyframe you can add a movement or application to your design. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (bezier) will be active. *

