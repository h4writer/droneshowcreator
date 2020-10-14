============================
5 Edit actions
============================

5.1 Menu bar
--------------

.. image:: images/menubar_edit_actions.jpg

5.1.1 File

.. image:: images/edit_actions_file.jpg

  5.1.1.1 Save

  *To save your layout.*

  5.1.1.2 Close

  *To close the edit actions submenu*

5.1.2 Edit

.. image:: images/edit-actions-edit.jpg

  5.1.2.1 undo

  *Undo an action or operation*

  5.1.2.2 Redo

  *Redo an action or operation*

5.1.3 View

.. image:: images/edit_actions_view.jpg

  5.1.3.1 Drone frames

  *You can choose whether or not the frame of the drone is shown in the visualization.*

  5.1.3.2 Drone closeness indicator

  *Function that indicates with a red block above the drone when the drones are placed too close to each other,and this cannot be performed in reality*

5.2 Buttonpane
----------------

5.2.1 Movement

*Here you will find all movement options that you can apply to your layout.*

  5.2.1.1 Bezier

  *A bezier is a parametric curve that consists of a connection between a starting point and an end point with anchor point. Used to draw straight lines, turns and curves that the drones take as their flight path. Be careful with a formation of drones, the center of the formation will always follow the curve. A layout can of course consist of a concatenation of several points, each intermediate point gets 2 anchor points to adjust the curve. Use the three cube icons front view, side view and top view to easily draw your path in depth and all dimensions.*

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

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (bezier) will be active. *

  5.2.1.2 Rotation

  *You can rotate the layout around various axes. Via properties you can enter different details for the desired rotation. See chapter 4.3.4 "properties" for more information.*

  - Properties

    - Start

      *Shows the time when a action rotation starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Rotation front, side, top

      *Here you can enter the number of degrees that the layout must be rotated according to 3 positions, front, side or top. The rotation point is automatically central to the layout.* 

    - Rotation point X Y Z

      *Here you can adjust the point where the rotation happens according to the X (= left, right), Y (= forward, backward) and Z (= top, bottom) axis. By default this point is placed in the middle point.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (rotation) will be active. *

  5.2.1.3 Move

  *Here you can move the layout from point A to point B in a rectilinear movement via properties you can enter various details for the desired move.*
  
  - Properties

    - Start

      *Shows the time when a action move starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Relative position X Y Z

      *Here you can determine the position according to the 3 axes to which the layout should move.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (move) will be active. *

  5.2.1.4 Scale

  *You can have the layout enlarged or reduced from a starting position, such as the effect of fireworks that burst open. Via properties you can enter various details for the desired move.*

  - Properties

    - Start

      *Shows the time when a action scale starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Scale X Y Z

      *You have the option to scale the layout of a clip or scene to a different format according to an X, Y and Z axis. Increasing the numerical value is increasing the format, decreasing the values ​​is decreasing the format. Use the arrows left and right or click on the value to enter a new number. Next to the word "scale" you will find a slider, if this is on you can scale in proportion. If the slide switch is off, you can choose which X (= left, right), Y (= forward, backward) and Z (= top, bottom) axis you want to scale separately.*

    - Scale point

      *Hier kan je het punt bepalen van waaruit de schaling gebeurd. U hebt de mogelijkheid om het schaalpunt te bepalen volgens de 3 assen (= left, right), Y (= forward, backward) and Z (= top, bottom)*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (scale) will be active. *

  5.2.1.5 Wave

  *With this function you can automatically add a wave movement to your layout. For example, the effect of a waving flag. Via properties you can enter various details for the desired wave.*

  - Properties

    - Start

      *Shows the time when a action wave starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Height

      *Here you determine the distance that the drone travels within its wave movement. The higher the number, the greater the wave movement.*

    - Time offset

      *This determines the time the drone will take from point A to point B to make the wave movement.*

    - Angle

      *This is the angle at which the wave will occur on the entire layout. If you place a grid and you take a wave of 0 ° it will move from left to right. At 90 ° the wave will move from back to front, and at 180 ° from right to left. Note, this function only works with the XV plane (=> this plane can be found in the start page => properties => plane).*

    - Iterations

      *Here you can enter the number of wave movements that the layout will make during the duration. Example: With a duration of 3 seconds and an iteration of 5, the format will make 5 waves during those 3 seconds.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (wave) will be active. *

  5.2.1.6 Yaw

  *xxxxxxxxxxxxxxxxxxxxxxxx*

  - Properties

    - Start

      *Shows the time when a action yaw starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Relative yaw

      *xxxxxxxxxxxxxxxxxxxxxxxt*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (yaw) will be active. *

5.2.2 Lights

*Here you will find all light effects and color options that you can apply to your layout.*

  5.2.2.1 Colorize

  *Giving a certain color to one or more drones. A color can be chosen from the color range or via custom color.*

  - Properties

    - Start

      *Shows the time when a actio colorizen starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Color
    
      *Decide here which color you want to use. You can enter a webcolor code via a # number. You can use the colors range or choose "custom color" for HSB or RGB colors.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (colorize) will be active. *

  5.2.2.2 Fade

  *Function where color A slowly fades and slowly changes into color B.*

  - Properties

    - Start

      *Shows the time when a action fade starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blend mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Color

      *tekstDecide here which color you want to use. You can enter a webcolor code via a # number. You can use the colors range or choose "custom color" for HSB or RGB colors.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (fade) will be active. *

  5.2.2.3 Gradiënt

  *Function in which the LED turns on and off, causing flashes of light on a regular basis. The discharge time can be set manually via properties.*

  - Properties

    - Start

      *Shows the time when a action gradiënt starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Start color

      *This is the color with which the gradient is started. you can choose from 3 options.*

      - Inherit

        *Inherit, here the program will always take the color that is just above the action in the timeline. Example row 1 = blue, row 2 = yellow and row 3 = gradient action => the gradient action on row 3 takes the color that is just above it, so from row 2 = yellow.*

      - Color

        *Here you choose a color yourself via the color fan, HSB color or RGB color.*

      - Random

        *The program will choose a color itself.*

    - Second color

      *It is the color with which the gradient ends, here too you have the same options as at the beginning color.*

    - Start position X Y Z
    
      *Determine the starting position where the gradient should start from the XYZ axis.*

    - Stop position X Y Z

      *Determine the starting position where the gradient should stop from the XYZ axis.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (gradiënt) will be active. *

  5.2.2.4 Fade-in

  *Function in which a color slowly emerges from black.*

  - Properties

    - Start

      *Shows the time when a action fade-in starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Easing

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (fade in) will be active. *

  5.2.2.5 Fade-out

  *Function in which a color slowly fades to black.*

  - Properties

    - Start

      *Shows the time when a action fade-out starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Easing

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (fade out) will be active. *

  5.2.2.6 Strobe

  *Function in which the LED turns on and off, causing flashes of light on a regular basis. The discharge time can be set manually via properties.*

  - Properties

    - Start

      *Shows the time when a action strobe starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Start color

      - Inherit

        *Inherit, here the program will always take the color that is just above the action in the timeline. Example row 1 = blue, row 2 = yellow and row 3 = gradient action => the gradient action on row 3 takes the color that is just above it, so from row 2 = yellow.*

      - Color

        *Here you choose a color yourself via the color fan, HSB color or RGB color.*

      - Random

        *The program will choose a color itself.*

    - Second color

      - Inherit

        *Inherit, here the program will always take the color that is just above the action in the timeline. Example row 1 = blue, row 2 = yellow and row 3 = gradient action => the gradient action on row 3 takes the color that is just above it, so from row 2 = yellow.*

      - Color

        *Here you choose a color yourself via the color fan, HSB color or RGB color.*

      - Random

        *The program will choose a color itself.*


    - Strobe duration

      *Here you determine how long the strobe's flash lasts. Expressed in milliseconds.*

    - Visible drones (%)

      *Here you can determine the number of drones that will flash simultaneously during the strobo action.*

    - Easing

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (strobe) will be active. **tekst*

  5.2.2.7 Sparkle

  *Function in which the LEDs turn on and off very quickly and are randomly distributed among all drones in the complete layout.*

  - Properties

    - Start

      *Shows the time when a action sparkle starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Start color

      - Inherit

        *Inherit, here the program will always take the color that is just above the action in the timeline. Example row 1 = blue, row 2 = yellow and row 3 = gradient action => the gradient action on row 3 takes the color that is just above it, so from row 2 = yellow.*

      - Color

        *Here you choose a color yourself via the color fan, HSB color or RGB color.*

      - Random

        *The program will choose a color itself.*

    - Second color

      - Inherit

        *Inherit, here the program will always take the color that is just above the action in the timeline. Example row 1 = blue, row 2 = yellow and row 3 = gradient action => the gradient action on row 3 takes the color that is just above it, so from row 2 = yellow.*

      - Color

        *Here you choose a color yourself via the color fan, HSB color or RGB color.*

      - Random

        *The program will choose a color itself.*

    - Strobe duration

      *Enter the duration for how long a light flash burns, expressed in milliseconds.*

    - Visible drones (%)

      *Here you can determine the number of drones that will flash simultaneously during the strobo action.*

    - Easing

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (sparkle) will be active. *

  5.2.2.8 Roll over

  *Function where color A will replace color B by rolling the color over the entire area of the layout.*

  - Properties

    - Start

      *Shows the time when a action roll over starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Start color

      - Inherit

        *Inherit, here the program will always take the color that is just above the action in the timeline. Example row 1 = blue, row 2 = yellow and row 3 = gradient action => the gradient action on row 3 takes the color that is just above it, so from row 2 = yellow.*

      - Color

        *Here you choose a color yourself via the color fan, HSB color or RGB color.*

      - Random

        *The program will choose a color itself.*

    - Second color

      *tekst*

    - Start position X Y Z

      *Determine the start position of the roll over via the XYZ axis.*

    - Stop position X Y Z

      *Determine the stop position of the roll over via the XYZ axis.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (roll over) will be active. *

  5.2.2.9 Spot

  *This function ensures that you can place a color accent at a specific place within the layout, just like a light beam from a spotlight.*

  - Properties

    - Start

      *Shows the time when a action spot starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Gradiënt type

      - Linear

        * De spot loopt van de ene uithoek naar een andere uithoek.*

      - Radial

        * De spot loopt vanuit het centrum van de opmaak naar buiten toe.

    - Start position

      *Determine the starting position of the spot along the XYZ axis.*

    - End position

      *Determine the stop position of the spot along the XYZ axis.*

    - Color

      *Decide here which color you want to use. You can enter a webcolor code via a # number. You can use the colors range or choose "custom color" for HSB or RGB colors.*

    - Keyframe blend mode

        - Fade between gradiënts
          
          *xxxxxxxxxxxxxxxxxxxxxxxxxxxx*

        - Match and adapt time offsets
          
          *xxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Cutt of after distance

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Gradiënt shift

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (spot) will be active. *

  5.2.2.10 Image

  *With this function it is possible to place an image over a grid of drones.*

  - Properties

    - Start

      *Shows the time when a action image starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Image

      * click on "none" to select a photo from the brouser and place it in the layout *

    - Middle X Y Z

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Up X Y Z

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Right X Y Z

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Scale

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Blur

      *xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (image) will be active. *

  5.2.2.11 Rainbow

  *With this function, a color gradient is automatically placed with the rainbow colors over the entire layout. The colors can be mutually adjusted.*

  - Properties

    - Start

      *Shows the time when a action rainbow starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Color

      *Decide here which color you want to use. You can enter a webcolor code via a # number. You can use the colors range or choose "custom color" for HSB or RGB colors.*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (rainbow) will be active. *

  5.2.2.12 Gamma correction

  *This is a non-linear function to correct the light intensity, luminance or brightness of a color. The amount of gamma correction not only changes the brightness but also the ratio of red-green-blue.*

  - Properties

    - Start

      *Shows the time when a action gamma correction starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Gamma

      *xxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (gamma corection) will be active. *

  5.2.2.13 Max light correction

  *xxxxxxxxxxxxxxxxxxxx*

  - Properties

    - Start

      *Shows the time when a action max light correction starts. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always adjust the starting position numerically.*

    - Duration

      *Specifies the duration of the action. The unit is displayed in milliseconds. 3,000ms = 3 sec. You can always numerically adjust the duration.*

    - Drones

      *With drones you can make a choice to which the action is applies. You can apply the action to all drones, then choose "all drones" or you can apply the action to one or more selected drones and then choose edit => select the drone => use selected drone*

    - Remove

      *With this button you delete the action that you have placed in the timeline.*

    - Blende mode

      *With blende mode you have different options to mix colors, an extra color on top of the basic color that is given from the start page.*

    - Opacity

      *The higher the number, the darker the color.*

    - Max light

      *xxxxxxxxxxxxxxxxxxxxxxx*

    - Keyframes

      * With a keyframe you can add a movement or application to your layout. On the basis of a start and end point, you can place this application on the timeline of your clip or scene and move it as desired. Between these two points the action (max light correction) will be active. *

5.3 Viewport
--------------

5.3.1 Cube icons

*The program has 3 different preview perspectives, the front view (first cube), top view (second cube) and the side view (third cube). A fourth function uses the directional arrows on the keyboard to allow you to freely move the layout in all directions for the ideal perspective. The latter function can be very useful when formatting complex structures.*

5.3.2 Chrono time

*This is the numerical representation of the cursor needle position in hours, minutes, seconds and milliseconds. If you adjust the numerical values ​​manually, the needle will automatically jump to the entered value.*

5.3.3 Play buttons

*The double arrows to the left: If you click on this, the cursor needle automatically jumps to the beginning of the timeline.
The play triangle: Clicking on this will cause the cursor needle to run from its position on the timeline.
The double arrows to the right: If you click on this, the cursor needle will automatically move to the end of the layout. This means to the end position of the last block
1x: This is the acceleration function, if you enter a value of 10x the playback speed will be accelerated 10x. The 1 value is the normal speed.*

5.3.4 Outlining icon

*The automatic framing icon ensures that your layout, regardless of size, is visualized in the available viewport frame. The percentage is automatically calculated for this.*

5.3.5 Visualisation in terms of percentage

*You can also manually determine the size of the visualization by entering a percentage yourself or by using the arrows. Manually determining the preview can be useful to enlarge details of complex structures for a clear interpretation.*

5.4 Properties
--------------

*See chapter 5.2 "Buttonpane*


5.5 Action list
----------------

*Each action, both movement and lights, is automatically placed in rows one below the other on the timeline when you click the + sign, next to the word row1, 2, 3 ... there is an eye icon. If you click on this icon, the eye will be crossed out, which means that the action is no longer applicable. Click on the eye again to reactivate the action. Place your mouse cursor on the timeline and roll the mouse wheel to zoom in or out on the timeline, this will enlarge or reduce the action blocks. You can also move the action blocks vertically for a different order if you wish, you will notice that when you drag a block down, new rows are added.*

5.6 Drone list
----------------

*xxxxxxxxxxxxxxxxxx*


