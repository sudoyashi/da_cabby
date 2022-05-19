 

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

The main thing benefit that comes from a carb conversion is the ability to revive a dying fuel system. Carburetors are mechanical devices and you got both the pros and cons in using them. They are analog devices, meaning you have to adjust every single detail to perform at its best. The simplicity of a carburetor makes it easy to service so long as your problem diagnosis is correct. Working on carbs is easy, but figuring out what to fix is the challenge.

For this conversion to go well, there will be many failures, and to find the right solution to those failures will take more than what this guide can provide. The principles behind the setup is simple, provide air and fuel at the correct ratios, but it's not exactly the most popular swap in the world. This isn't engine swap complexity, but it can get close if you are building your own air/fuel system. So, as someone that has done a bike carburetor swap, stick with your current fuel system and only do a carb swap to the mainstream Webers, or other DCOE carbs. There are no specific positives that warrant a bike swap as your primary option. But why did it do it? Instant torque. A visceral intake sound. And it was a lot cheaper than doing an engine swap!

But, I chose the bike carburetors for a reason: it looked like a pretty fun challenge!

~~ Parts and materials for a bike carb 
Here is a list of parts I can remember using. The number of combinations and solutions to the odds and ends of this project is limitless. Thus, use this as a guide instead of an end-all, be-all because you're definitely going to need more than what I have here.

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

### Heat, Fuel, and Engine Management (optional, but recommended)
- Heat shields 
- Fuel heat sheathe
- Fuel pressure gauge
- Air fuel ratio gauge
- Carburetor synchronizer

### Recommended tools

- Respirator for vapor and particulate matter
- Safety glasses
- Fire extinguisher
- General hand toolset
- Long Phillip head screwdriver
- Long flat head screwdriver
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

I would say a majority of these tools come pretty standard in a well-equipped DIY garage. You may need to buy or borrow other carburetor and tuning specific tools like:
- A vacuum-mercury gauge
- AFR gauge, 

CO2 gauge, fuel pressure gauge, and smoke tester.

You need to think about this fuel system change like an undocumented engine swap. There are probably a handful of people in the world that have done the same setup and goals. The more common your car, the more common the setup, and the easier you will have it. If you have a hand in carburetors, that's great too!

Others might have a different cam, new exhaust, etc. Think of this as a primer to your carb conversion. You need to understand tuning, carburetors, vacuum, heat management, plumbing, and electrical work. Once you remove the manufacturer's original design, you are ruin the balance of drivability, power, and reliability. 

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

Removing the current system is pretty straightforward, but don't go ripping out every single component. We'll look at the process I went through with the Golf.

The basics of removing the current fueling system  start from the fuel pump. You can assess what you need and don't need. I kept the in-tank fuel pump since that acted more as a sender from the fuel tank. In the original design of the Golf, two fuel pumps exists: the in-tank one and the pressurized one outside of the pump. I removed the outside one, connected it to the fuel tank along with the accumulator. From the rear of the car, I also removed whichever fittings I could and temporarily removed the hoses to the fuel return. 

At the time, I was not sure what to do with the fuel return, so I just capped it off and both ends, keeping it there just in case for the future.
## 2. Modify the fuel delivery system

Starting from the tank, be positive you have a clean tank! Check the inside of the tank and make note if you have a fuel sending unit with the float and fuel pump, be sure they are in good working order. The float will measure the fuel in your tank and usually, it comes packaged with the fuel pump right next to it. In combination, this in-tank system pulls out the fuel from the fuel tank. However, the Mk1 has a different setup.

There are TWO fuel pumps for the Mk1, one inside and one outside! Inside the tank is a lift pump that will lift fuel from the tank through the lines, the second pump is what pressurizes the fuel to 43.5 PSI~. It passes through a fuel accumulator to accumulate fuel, aiding the car for cold starts. This is like the function of a choke. The accumulator also helps to mitigate pulsations from the fuel pump itself.

In my case, we replaced the second pump that pressurizes to 43.5 PSI. Replacing this pump made it simpler to hook up this system. As the car runs, it will only be able to generate up to 3 PSI of fuel, which is enough for the carbs that I am running. 3 PSI is not a rule-of-thumb for all carb conversion setups, it is what works for my specific carburetors that came from a 98 ZX6R. According to the manuals that I've found, it runs at about 3 PSI. The best thing to do is search for a replacement fuel pump for your specific bike carb source, this way you can get the most correct PSI possible.

Once you solve the pumping setup, we need to filter the fuel. Most in-tank filters come with a screen where it pulls the fuel. After the tank, you may install a filter after the fuel pump and in the engine bay. Test with a fuel pressure gauge so that it is not too restrictive, otherwise opt for a single filter. In my case, I added both filters. I am keeping an eye on this, but so far it seems okay. 

To plumb the fuel line, there is the cheap way and the expensive way. To do it cheaply, stick with rubber fuel lines, hose clamps, and adapters. To do it properly, steel-braided fuel lines, spring clamps, and high-quality adapters with proper flares (like for AN fittings). Considering this is a low PSI application, it seemed fine to use the regular fuel line versus the stainless steel braided line. Run the lines from the tank to the carbs accounting for the fuel pump, filters, fuel pressure gauge, and maybe a charcoal canister. Most fuel pumps run on a 12V circuit, so test your circuit and fuse it. In the engine bay, consider heat management if your line is going to run near the exhaust manifold. Confirm all your lines, and pressurize your system for leaks by turning your system on and running your fuel pump.

If everything works as normal, congratulations, you assembled a fuel system! Not everyone can say that, now can they? Well, let's make sure it works, next up, are the air and vacuum systems.

## 3. Vacuum and Carburetors

The vacuum system is simple but can get tedious and complex as the days go on. The work is not difficult, but it can become a pain to diagnose without the aid of a few tools. A smoke tester and a carburetor synchronizer tool.

With your car's original intake system gone, you need to trace from your intake holes to all other parts of your vehicle that utilize vacuum, think of your brake booster, charcoal emissions, vacuum-based systems like distributors, shift lights, even extending over to tachometers. There are many applications for the big air pump in your car and vacuum is a big part of making carburetors work well. Unfortunately, tracing a vacuum leak is quite difficult if you're not sure what happened. By using a smoke tester, you can push smoke through your vacuum system enough to see where a leak might occur! The smoke should reach the intake side of the fuel system, and if there are no more leaks, then you are all sealed from there. The hard part is getting there!

This was the most challenging part of my whole build. I could not find a way to seal my vacuum leaks without spending a good chunk of money refinishing, surfacing, and making new parts. It was a pain...

Attach your carburetors to your head with a custom manifold and flange suited to fit the orifices of your carbs, and adapt them with fuel-resistant, fluoro-lined hoses. Using good clamps will save you in the long run instead of the regular worm clamps. Worm clamps are the simplest and cheapest, but they don't seal as well and you can risk biting into your hoses if you go too far. Spring clamps are very good clamps but can be hard to use if they are going to be in tight spaces. The ones I recommend are T-Bolt clamps, functioning just like a worm clamp but with the security of a circular bite as good as a spring clamp.

Instead of biting from the torque point, the entire inner surface clamps onto the hose. Use the T-bolt clamps at the most crucial point: the intake manifold. In all other areas, use worm or spring clamps to secure the vacuum and fuel lines. Some vacuum lines probably won't need clamps if you're using barbed fittings to join them.  

Once the entire system is nearly complete. We can almost start the car!

## 5. Testing! Checks before the first start.

To avoid damaging your engine, do whatever you need to do to prevent your plugs from combusting the AFR mixture. You can pull spark plugs, disconnect all the spark plug wires, or disconnect the main coil wire.

- Prime your fuel pump, fill the lines with fuel to get good pressure. Turn the car on and off to get fuel flowing through your fuel lines. Check for leaks.
- Smoke the vacuum system, and double-check your vacuum system to see if there are any leaks. Smoke should only come out of your carburetors. If there are leaks
- Check your throttle cable and other mechanical linkages. Pull your cable to make sure there is no binding across the throttle range.
- Check your fuel pressure, be sure it's the correct fuel pressure for your carbs. If it's low, check your fuel filter and check for blockages or kinks in your hoses. If it's too high, your pump might be faulty. 

If everything goes smooth from here, attempt to start the car. Wire up all your plugs, coil, and fuel lines, clean up the engine bay, and attempt to start the car. If it starts, congrats! **If it doesn't start, here are some issues you could be running into.**

### Potential Issues:

We have to start a good amount of assumptions before diagnosing anything. Jumping to conclusions won't yield a good diagnosis. Trying to start a car after working on it for months would leave your gas a little stale. Do you even know if you have enough gas? Don't make too many changes before knowing exactly where the baseline is. At this point, let's challenge our assumptions:
- Is my engine healthy? Compression, valves, timing, are they all ok?
- Fluids? Oil, coolant, gas
- Tension? Timing belt, serpentine, other auxiliary belts up to spec
- Leaks? Air or oil leaks?
- Electrical issues? Is my car properly grounded? Is my battery charged? Is my alternator okay? Am I getting spark?

Remember the five elements needed to start an engine:
- Spark
- Air
- Fuel
- Compression
- Timing

If you passed the assumptions test, then let's look a little deeper and diagnose our issues.

Is there a hissing noise when you use the starter?
- Check for vacuum leaks. The hissing could be the air coming in through a small hole or leak. This is known as unmetered air. While we do want more air for the engine to create more power, unmetered air is unaccounted and will through your AFR out of balance. Let's start the car on a good note.

Car starts, then dies, but can start again?
- This could be a number of things.

Cranking, but takes a while to start the car? 
- Assuming you have correct vacuum, adequate fuel pressure, and no leaks, not starting could mean your AFR mixture is too lean. Your engine is cold and needs more fuel to start a combustion cycle. Let the car cool down then try to start the car with starter fluid. If it starts normally, let the car warm up, then adjust your AFR. 

After letting the car warm up, I turn off the car, but the violently engine spins over again before stopping completely!
- This is called dieseling. Diesel engines work with heat and compression and do not use spark for ignition. When you turn off the car, there is leftover air and fuel in the combustion chambers, hence a short term turnover until the engine depletes the leftover fuel. It's not only dangerous and unhealthy for your engine, but it's very annoying.

Challenge you assumptions, challenge your answers. Every setup is different in this conversion and you are the most aware of what changes were made to the car. The problem can always be solved with enough money.

## 7. First drive to the gas station

FINALLY. 

Driving your project car on the block is a validation that your car still works after making so many changes to the car. Start the car and let it warm up to give it the best chance of surviving your drive. Don't forget about your brakes and lights, the vacuum system is connected to your brake booster right? It's good that you have a working engine, but safety becomes more important after making these modifications. If everything checks out, roll out of your driveway and see if you can make it back. If you're feeling brave, take it on a public road. And if you're really brave, go to the drive-thru.

I went to the gas station for my first trip since I really needed to fill up some gas to sub out the old gas. Get a feel for the suspension, brakes, mobility, and throttle response. See how the car changed. You could be faster too! But I'd say that you sound faster than you look with motorcycle carburetors. 


## 8. Tuning sessions
Carb heads will shine here, we're tuning the carburetors for the best performance across the throttle range.

Our goals is to hit these target AFR ratios to balance performance and efficiency.
https://www.safrtool.com/SAFR-AFR-values.asp

- 6 AFR - Rich Burn Limit
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

It is best to avoid AFR below 12 and above 15 in normal driving conditions. Exceptions to this are when you immediately open and close the throttle, these AFR spikes are outliers.


## 9. Final adjustments
The final step is to perfect your setup! Projects will never be "finished", but there will be a point where you won't be breaking down every other time you drive it. And that my friend is the time to celebrate. This is where you can truly enjoy your car with only minor maintenance issues.

Depending on how far of a modification you have gone, most likely, you made the car worse off in some ways, haha. This rings true across almost all aftermarket modifications. Reliability and drivability are dependent on your ability to engineer and solve mechanical issues.

In this stage you will want to resolve these things:
- Throttle cable position
- Ideal idle RPM
- Tuning for power or tuning for efficiency
- Reliable parts
- More heat management

There aren't too many things left to do except perfect the setup you have. Finding the optimal settings for fuel, air, vacuum, and heat in varying degrees of weather and performance is what you are trying to accomplish. This is where goal setting helps to guide your direction. Do you want to improve performance? Improve torque, improve reliability, and improve maintainability. 



## Summary

Congratulations! You have truly modified your car and graduated from a simple bolt-on boy to a carbureted crook. 

This is a lengthy process that is going to take more than buying the simple bolt-on parts to make this run well. This build is going to take a lot more dedication and attention to detail than you would imagine and hopefully when you reach the end, you will understand how your car is running. 

Consequently, your ability to diagnose, engineer, and solve problems will grow. And by the end of it all, don't forget to hoon the fuck out of your neighborhood with one of the most beautiful, visceral sounds of carburetors.

Your car may not be faster.
Your car may not be strong.
Your car may not even run at all!

But when your car is on the road, cruising along in the end, you can own up to this car. It's something that you have modified and changed, for better or worse. Take pride in your work.