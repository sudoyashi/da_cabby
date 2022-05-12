---
layout: post
title:  "TITLE"
date:   2022-05-15 00:00:00 -1000
categories: bike carb conversion
---
My complete write-up on converting a car's fuel system from fuel injection to bike carburetors.

~ Introduction: What is the point?

Bike carb conversion are not very common and don't seem to get too much good coverage. So why would you do it? I can only really think of two reasons why you should even go through with this:
1. As a proof-of-concept on a shitty car you don't care about
2. Another way to revive your car's failing fuel system

The main thing with this conversion is this is not a conversion for power but a conversion to make a running car on a different budget than an engine swap or ECU install. Carburetors are largely mechanical devices and you got both the positives and negatives that come with using carburetors. To name a few, carburetors are dead simple when it comes to their functionality. However, it comes at the price of understanding those simple mechanics and relying more on yourself as a home mechanic to diagnose the issues you've made.

For many cars, this is not a very straightforward process and you will likely go through numerous iterations, failures, and problems that will take more than what this guide, or any guide for that matter, can provide for you. It's not that it is exactly difficult, but because it remains undocumented without much information on the web as compared to engine swaps. This isn't engine swap complexity, but it can get close if you are rebuilding your fuel system from the ground-up. Therefore, as someone that has done a bike carburetor swap, I would suggest trying to stay with your current system, swap to a more common Weber or other DCOE carburetor conversion, or swap an engine in with an ECU completely. There are no specific positives that warrant a bike swap as your primary option.

But, I chose the bike carburetors for a reason: it looked pretty fun!

~~ Parts and materials for a bike carb conversion

I will try to list as many parts I can remember using but there were so many odds and ends in the end because of tweaking and tuning on my own that I could have forgotten some things. This list should be a guideline of what you need, you're definitely going to need more than just what I have here.

### Essential parts

- 4-barrel bike carburetors
- Custom intake manifold
- Fuel line kit for fuel IN
- Fuel line kit for fuel RETURN
- Fuel filter
- Fuel and vapor separator
- Fuel pump, specific to the carburetors OR
- Fuel pressure regulator
- Carburetor air intake hose
- Carburetor vacuum lines and fittings

### Plumbing parts

- Hose clamps for air (vacuum and intake)
- Hose clamps for fuel (fuel)
- Hold-down clamps for fuel hose
- Hose plugs and caps for testing

### Carburetor parts

- Stock, factory pilot, main, needle jet parts
- Larger jets for modifications in setup
- Longer adjustable idle mixture screw
- Spare fuel bowl gaskets
- Spare float bowl parts (hinge, level, screw)
- Throttle cable kit

### Heat, Fuel, and Engine Management
- Heatshields 
- Fuel heat sheathe
- Fuel pressure gauge
- Air fuel ratio gauge
- Carburetor synchronizers


### Recommended tools

- Respirator
- Safety glasses
- Fire extinguisher
- General hand tool set
- Long Phillip head screwdriver
- Long flat head screwdrive
- Calipers
- Smoke/leak detection system
- Vacuum tester
- Timing light
- Various picks
- Various pipe cleaners and other cleaning supplies
- Various Allen head fasteners, wrenches, and other spare hardware
- Throttle cable cutters
- Wire strippers
- Wire crimps
- Wire crimp connectors
- 18AWG and 12AWG wire kits, 3 or 4 colors would be nice 
- Voltmeter
- Hose cutters or new, sharp, blades

I would say a majority of these tools come pretty standard in a well-equipped DIY garage. The only tools that might be missing are carburetor-specific tools or engineer tuning tools like vacuum synchronizers (mercury or nonmercury), an air-fuel ratio gauge, a fuel pressure gauge, a smoke tester, and so on.

You need to think about this fuel system change like an undocumented engine swap. There are probably a handful of people in the world that have done the same setup and goals. The more common your car, the more common the setup, and the easier you will have it. If you have a hand in carburetors, that's great too!

Others might have a different cam, new exhaust, etc. There are a plethora of deviations for a fuel system conversion, and it only grows with engine swaps! Think of this as a primer to that. You are going to NEED to understand tuning, how carburetors work, the purpose of vacuum for an engine, understanding the difficulties of fueling with vapor lock, heat management, routing, and organization. It's all a consequence of changing your fuel system so you need to understand what is happening in order to diagnose and resolve any issues because there will DEFINITELY be issues.

May 15, 2022: There may be other tools I'm missing for now, but I'll edit this more when I can remember.

### The Conversion Roadmap

Once you have officially determined that your current fuel system is too expensive or too difficult to replace, we can talk about carb conversions. I would still urge people to reconsider repairing their current system over replacing it because of the added complexity and limited support you will have. Unless you really want to get into the weeds of what it means to have a project car, steer clear.

We can break the conversion into these major steps:
1. Remove the current fuel injection system 
2. Modify fuel lines inlet and return, replace or install pump, filters, gauges
3. Modify air and vacuum, brake booster, and other vacuum references
4. Install carburetors with custom flange and manifold
5. Testing for air, vacuum, and fuel leaks
6. Install auxiliaries, throttle cable, gauges, 
6. First start, first drive to 7-Eleven
7. Tuning under general driving conditions
8. Final adjustments

This is the ideal sequence of events that would happen provided that everything goes smoothly! But, I'm willing to bet that this is NOT going to happen. If it does happen as smoothly as possible, wonderful. But let's not get our hopes up. Let's begin with step 1.

## 1. Remove the current fuel injection system
## 2. Modify the fuel delivery system
## 3. Modify the air and vacuum systems
## 4. Install carburetors
## 5. Testing for air, vacuum, and fuel leaks
## 6. Install auxiliaries 
## 7. First start, first drive to 7-Eleven
## 8. Tuning sessions
Carb heads will shine here, we're tuning the carburetors for optimum performance across the throttle range.

Our goals will be to hit these target AFR ratios based on a combination of reliability, performance, and costs.
https://www.safrtool.com/SAFR-AFR-values.asp

- 6 AFR - Rich Burn Limit (engine fully warm)
- 9 AFR - Black Smoke | Low Power
- 11.5 AFR - Best Rich Torque at Wide Open Throttle (WOT)
- 12.2 AFR - Safe Best Power at Wide Open Throttle (WOT)
- 13.3 AFR - Lean Best Torque
- 14.6 AFR - Stoichimometirc Air/Fuel Ratio Value (Stoich)
- 15.5 AFR - Lean Cruise
- 16.5 AFR - Usual Best Economy
- 18 AFR - Carbureted Lean Burn Limit
- 22+ AFR - EEC / EFI Lean Burn Limit

Taking the goals from the website gives us a strong baseline before we start going crazy.
- Idle / light cruise: 13.5 AFR
- Cruising: 14 AFR
- Wide Open Throttle: 12.5 AFR
- Acceleration 12 AFR

## 9. Final adjustments
The final steps in perfecting your setup! Arguably, projects will never be "finished" but there will be a point where you won't be breaking down every other time you drive it, a time where you can truly enjoy your car with only minor maintenance issues. This is what you are aiming for.

Depending on how far of a modification you have gone, most likely, you probably made the car worse off in some ways, haha. Reliability and drivabillity are entirely dependent on your ability to engineer and solve mechanical issues. Henceforth, this section is dedicated to that.

In this stage you will probably want to resolve these things:
- Throttle cable position
- Ideal idle RPM
- Tuning for power or tuning for efficiency
- Reliable parts
- More heat management

There aren't too many things left to do except perfect the setup you have. Finding the optimal settings for fuel, air, vacuum, and heat in varying degrees of weather and performance is what you are trying to accomplish. This is where goal  setting helps to guide your direction. Do you want to improve performance, improve torque, improve reliability, improve maintainability. 


## Summary

Congratulations, you have truly modified your car and graduated from a simple bolt-on boy to a carbureted crook. 

This is definitely a lengthy process that is going to take more than just buying the simple bolt-on parts to make this run really well. This build is going to take a lot more dedication and attention to detail than you would imagine and hopefully when you reach the end, you will really understand how your car is running, improve your diagnostics ability, and hoon the fuck out of your neighborhood with one of the most beautiful sound that come as close to the raw, visceral sound of individual throttle bodies without the immense cost. 

Your car may not be faster.
Your car may not be strong.
Your car may not even run at all!

But when your car is on the road, cruising along in the end, you can really own up to this car. It's something that you have really modified and changed, for better or worse. Take pride in your work.