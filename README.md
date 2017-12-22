This is a tracker application for notifying our day to day activity pattern, and highlighting anomalies in case.

It has  important components - Schedule extraction which is designed on a sliding window approach, and activity identification which works on rate of change of GPS co-ordinates. Since this data is streaming, we notify anomalies for those location-timestamp tags that do not fall in the extracted schedule of the user.
