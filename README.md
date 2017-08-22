# ArcLayoutTest
环形布局

ArcLayout

attr	            description
arc_origin	      Center of the arc on layout. All of patterns that can be specified, see the demo app.
arc_color  	      Arc Shaped color
arc_radius	      Radius of the layout
arc_axisRadius	  Radius the axis of the child views
arc_freeAngle	    If set to true, each child view can set the free angle, default false
arc_reverseAngle	If set to true, reverse the order of the child, default false. Note: If arc_freeAngle set to true does not work

Child views in ArcLayout

attr	      description
arc_origin	Set the origin point of arc_axisRadius as well as layout_gravity, default center
arc_angle	  If arc_freeAngle set to true, layout the specified angle
