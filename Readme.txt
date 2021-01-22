the first row is vehicle number 
the second row is vehicle's capacity

[Depot]/[Node]
idx;  x-coordinate;  y-coordinate; 0; 0;

[Pickup]/[pickup]
idx;  x-coordinate;  y-coordinate; maximum ride time; load; profit; earliest time window; latest time window.

[Delivery]/[delivery]
idx;  x-coordinate;  y-coordinate; 0; load; profit; earliest time window; latest time window.


[Speed 0]
[Speed 1]
[Speed 2]
[Speed 3]
[Speed 4]
Five time zone with different speed profile: 
For instances : " 0.0 120.0 0.0 0.5" : means from time 0 to time 120, the speed is set to 0.5

[speed choose matrix]
For each arc, it has a speed profile.
For instances:  the link (0,4) is assigned with speed profile 1, which is given by [Speed 1].

