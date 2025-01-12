We love the [Hackaday Supercon 8 Add On Badge](https://github.com/Hack-a-Day/2024-Supercon-8-Add-On-Badge),
but in our opinion it has two major design flaws:
1. 4 out of 6 SAO slots are oriented sideways or upside-down
2. there is a large empty area in the center of the badge

We present two simple adapters to solve these issues.

![Supercon 8 badge without and with adapters](img/s8-sao-badge.jpg)

**SAO Up** rotates the SAO slot by 90 degrees, orienting SAOs closer to
their upright position. The same PCB works for the left and right side
of the badge, depending on which side the SAO headers are soldered.

![SAO Up adapter](img/s8-sao-up.jpg)

**SAO Bridge** adds an SAO slot in the center of the badge, and also
rotates the left and right SAO slots into upright orientation. The center
slot is connected the power and I2C of the bus on the left side of the
badge (slot 2).

![SAO Bridge adapter](img/s8-sao-bridge.jpg)

Black would have been the logical color for the adapters. But we only had
10 days between [badge reveal](https://hackaday.com/2024/10/22/the-2024-hackaday-supercon-sao-badge-reveal/)
and the event, so we went with green as that offered the fastest
turnaround time at JLCPCB.

You are welcome to duplicate, adapt or steal this project. The license is
CERN-OHL-P, which is open and permissive.
