---
permalink: /emergencypower
title: "DIY Emergency Power System"
date: 2020-02-20
---

# General note
This is an update to a previous article I wrote in 2019. Having just survived a
five-day power outage, the solution described worked quite well. However, in
the time since I wrote the first article, I have learned a lot. This new post
presents my updated learnings and recommendations.

# Abstract
This article discusses how to design and build a neighbor-friendly,
city-noise-code-compliant multi-day emergency power solution using rechargeable
lead-acid batteries, power inverters, and generators. Alternatives such as
using a car, solar panels, transfer cutoff switches, whole-house generators,
and Tesla Powerwalls are also discussed.

# Motivation
Multi-day power outages, especially in the winter, can provide many challenges:
lighting, heating, bathing, food preparation, communications (Internet), and
boredom.

In the summer, heating and lighting is less of a concern, but food storage and
preservation becomes an issue.

By prioriting essential needs, the energy needs of a house during power outages
may be quite modest and could be met by a battery-powered system.

Battery powered systems are preferrable to the alternatives because they do not
require ventilation and require much less maintenance. Perhaps most
importantly, they reduce neighborhood angst by being as quiet as possible,
especially at night during sleeping time.

While it is tempting (if money is not a concern) to set up an automatic
whole-house generator, this is more suitable for rural living. If you live
within the city limits, it is pretty much guaranteed that your neighbors will
hate you for a whole-house generator. And, indee , fossil-fuel generators are
obnoxious. The solution presented in this post takes into account the
"good-neighbor" philosophy necessary in any urban setting.


Minimum Viable Solution
=======================
This is unchanged from my previous recommendation. It is the cheapest and
easiest solution.

However, power outages in my neighborhood are becoming more frequent and more
severe, extending into many days. I thus started to think about enhancements to
the minimum viable solution.

For our family, the primary concern during a power outage is Internet. The
Minimum Viable Solution performed spectacularly for this purpose. With a single
100Ah battery, we were able to run almost 24 hours with just Internet (cable
modem plus Wi-Fi) and charing phones and laptops. For short outages, less than
1-2 days, this was perfectly adequate.

In addition, because we have a tankless natural gas hot water heater, we also
were able to have hot water. (The tankless water heater requires minimal
electricty to run, about 7 watts, which is easily provided by the inverter.)

Some of the hassles of the Minimum Viable Solution included:
- Extension cords running everywhere
- Dishes piling up in the sink (no dishwasher)
- No furnace heat. (We burned wood and used propane heaters to stay warm.)

What worked well:
- We only used the generator from around 2pm to 7pm. I haven't checked with the
  neighbors yet, but hopefully they weren't too annoyed by the generator during
  these hours.
- We tried to charge laptops and use the hot water when the generator was
  running. Overnight, only the Internet was kept running.


Upgraded Solution
=================

First, we are adding a second 100Ah battery, for 200Ah in total. This will give
us even more time that we can run on battery without having to run the
generator.

I also am adding a digital monitor that will tell how many amps have been
consumed and the estimated time left at the current consumption.

I purchased all of these items from Amazon. The items often do go on sale or
can be purchased from Amazon Warehouse Deals for a substantial savings.

I decided to get a different charger, the Iota Engineering DL-90. It is a 90
amp charger, over four times as powerful as my previous charger. Also it can
charge the battery while it is under load, meaning I can avoid the temporary
downtime on our Internet connection by leaving everything connected when
charging the battery.


LiFePO vs AGM
=============
I briefly investigated Lithium Iron Posphate (LiFePO or LFP) and it may be the
right solution for some people. LFP batteries can provide much higher current
and can charge more quickly than AGM batteries. They also can be almost fully
depleted (called depth of discharge or DOD) without any adverse effects,
whereas depleting an AGM battery below 50% will shorten its life span.

LFP are extremely popular in the solar and RV communities where the batteries
are a primary power source and are continously being charged and discharged.
For the home emergecny backup situation that is only used a few times a year,
these attributes are less important.


12V lead acid battery
---------------------
[![Battery](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B00S1RT58C&Format=_SL160_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=prestoschoice-20&language=en_US)](https://amzn.to/2N3NUUK)

You will need a battery that can store a lot of energy. I recommend that
everybody start out with a 100Ah battery like the [Universal
UB121000](https://amzn.to/2N3NUUK) (I paid $168). This battery was able to
power my 30-year-old refrigerator for almost 24 hours.

This battery can provide 1 amp for 100 hours, 10 amps for 10 hours, 100 amps
for 1 hour, etc. See the power discussion in the inverter section below.

If after setting up the system and doing a practice run, you decide that you
need more power, then you can purchase additional batteries and connect them
together.

Note the life expectancy of the battery is around 5 years. You may consider
staggering purchases of new batteries every 3-4 years to ensure that a working
battery is always available. The older batteries can be kept in service,
providing power until they die.

Inverter
--------
[![Inverter](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B06XPRJ1HB&Format=_SL160_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=prestoschoice-20&language=en_US)](https://amzn.to/2BzfVih)

For most people, I recommend getting a 1500W inverter such as the [VertaMax
Pure Sine Wave 1500](https://amzn.to/2BzfVih).

This will be powerful enough to power a microwave oven for short amounts of
time should you need to do that. It should be able to easily handle most
household needs, such as refrigerators, Internet routers, laptop and phone
chargers, etc. Note that using a lot of watts will quickly drain the battery.
If run at a full 1500W, the inverter will drain a 100Ah battery in about 40
minutes.

Unlike many other inverters, this one comes with the proper cables, connecting
hardware, and fuses that you need.

This is a sine wave inverter, which is more expensive but provides cleaner
power. The alternative is "modified sine wave" inverters, which may cause
problems for sensitive electronics and may cause motors and compressors to run
hotter than normal.

It is possible to order a smaller or larger inverter, but you will need to
calculate your exact power needs. The easiest way is to check this [list of
energy
amps](https://www.metrosolarmatics.com/applliance-wattsamps-calculator.html).
For example, a TV is listed at 100W. Divide the total watts by 10 and that will
give the approximate number of battery amps used per hour. If you are using the
100Ah battery recommended above, a 100W TV would pull 10A and thus the battery
would last for 10 hours.

Charger
-------
[![Charger](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B07CZ7KWP3&Format=_SL160_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=prestoschoice-20&language=en_US)](https://amzn.to/2N2VChP)

The [LST 12V Battery Trickle Charger](https://amzn.to/2N2VChP) charger
recharges the battery and keeps it fully charged so that it is ready when
needed. The charger automatically performs periodic maintenance on the battery,
which is required of lead acid batteries.

This charger will take 20 hours to fully charge a 100Ah battery. For faster
options, please see the upgrade options below.


Upgrade Options
===============

Gas-powered generator
---------------------
If the battery runs out during a power outage, a gas-powered generator inverter
can be used to recharge it.

I purchased a [Sportsman 800W Gasoline Digital Inverter
Generator](https://www.homedepot.com/p/Sportsman-1-000-800-Watt-Gasoline-Powered-Digital-Inverter-Generator-802085/300792167)
from Home Depot for $158 on sale.

Gasoline is not shelf stable and requires a
[stabilizer](https://amzn.to/2E8XwKS) for long term storage. The stabilizer
should be added every 12 months. The stabilizer itself is only good for 2 years
once opened, so don't buy large quantities. You also should plan on running
your generator every 6-12 months to check that it is working.  Finally, make
sure not to leave any fuel in the generator when you store it.

Faster charger
--------------
[![Fast Charger](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B00F5EBS66&Format=_SL160_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=prestoschoice-20&language=en_US)](https://amzn.to/2Go5lPh)

The [ProMariner 43020 ProSport 20](https://amzn.to/2Go5lPh) will charge the
battery much more quickly. It can charge a 100Ah battery in about 5 hours. If
you are going to try and use a gas generator to recharge the battery during
power outages, this is the only practical option. Note that the battery cannot
have a load on it (e.g., cannot be powering an inverter) while it is being
charged with this charger.


Commercial alternatives
=======================
[![Goal zero](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B007Q23YC6&Format=_SL160_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=prestoschoice-20&language=en_US)](https://amzn.to/2TPcH1g)

If the DIY solution above looks like too much trouble for you, you can purchase the same thing in a polished product with customer support, a warranty, etc. Check out the [Goal Zero Yeti 1250](https://amzn.to/2TPcH1g).


Review of other solutions
=========================
Many other options are available however cost is usually the main factor for
most households.

**Whole house standby generators** powered by natural gas will provide automatic
failover. These require professional electrician installation as well as a
natural gas meter upgrade. The systems may require annual maintenance. The
natural gas pipes may rupture in a seismic event, defeating the entire
solution. Lastly, the cost is prohibitive for many at $15,000 or more.

**Gas or propane generators** are relatively inexpensive for the amount of power
they provide. Propane fuel is shelf-stable and readily available. Gas requires
treatment for storage and even then has a maximum shelf life of 2 years.
Generators require ventilation and must be run outside. Generators are quite
loud. Unused fuel should not be left in a generator. Generators produce power
by using an engine to turn an alternator that produces AC power. Unfortunately
the power produced is “rougher” than AC power from the power company, which may
cause problems for sensitive electronic devices.

**Inverter generators** are similar to regular generators but they solve two
problems: noise and AC power quality. Inverter generators are usually much
quieter than normal generators. Inverter generators produce power in a similar
way to regular generators, but they add an additional step where the AC power
is converted to DC and then back to AC again, which produces much cleaner AC
power. The downside to inverter generators is that they are substantially more
expensive than regular generators.

Solar power
===========
[![Solar panel](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B07GF5JY35&Format=_SL160_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=prestoschoice-20&language=en_US)](https://amzn.to/2GEUIXL)

The ultimate solution would use a solar panel to charge the battery. I have not
investigated this, but the first step would be getting a solar panel, like the
[Renogy 100 Watt 12 Volt Monocrystalline Solar Panel](https://amzn.to/2GEUIXL).

Flexible panel is much lighter, not much more money, probably a better
solution: [WindyNation 100W 100 Watt 12V Bendable Flexible Thin Lightweight
Monocrystalline Solar Panel](https://amzn.to/2GE8dad).

Also need a [controller](https://amzn.to/2TPboPR).

This is an area for future research.
