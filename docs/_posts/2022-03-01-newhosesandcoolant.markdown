---
layout: post
title:  "Installs - From single to dual rounds, new power steering linees and G13 coolant"
date:   2022-03-04 00:00:00 -1000
categories: power steering, coolant, radiator, cooling, ps
---

# Finally installing dual round headlights!

I've always lusted for the Euro style quad headlights because it's reminiscence to the classic four-light setup on E30s and classic Mercs. Like popup headlights to JDM cars, the dual round headlights on a Golf Mk1 is the Golf that I imagine in my head. 

I picked this grill up from a buddy named Robert in Waipahu, Hawaii. It's weird to name these smaller towns in Hawaii like Waipahu, Kalihi, or Mililani in the form like they're their own city. On the island of O'ahu our true "city" by legal address is generally Honolulu; hence, it is Honolulu, Hawaii. Robert was a very knowledgeable guy that had the parts that I was looking for:
- Spare AC vents that came from a '91 Golf
- The dual round headlight grill from the same parts car

The practical reason I wanted the dual round lights was it could provide with more lighting during the night. These H4 lights aren't as bright as the modern day HID, but replacing these filament bulbs with LEDs would definitely change the look of the car that I think wouldn't look great. I've seen angel eyes and crosshairs on other builds, but those Golf Mk1s were a lot cleaner than mines, haha.

## Tools and Supplies

- Wire crimpers or soldering iron with flux-core solder
- Wire cutters
- Scissors
- Multimeter

- Wires, 12 AWG and 18 AWG
- Fabric, high-heat Tesa tap OR electrical tape OR liquid electric tape
- Wire crimp connectors
- Wire loom
- Vampire clips, t-taps, or splice taps. Whatever you call 'em. 

## Dual round installation

There's a couple ways that we could go around this. I went to do my own harness rather than tapping into the current wiring.

I believe the original setup utilized the inner round lights to work in tandem with the high beams. On the low beams, the lights would be off. On the high beams, the lights would be on. This would mean that it would share a common ground and receive power from the high beam positive wire.

In my setup, I separated them to have more control. Also because I'm lazy. I had originally installed lights on my bumper with a separate harness, but they ended up looking terrible. I removed those lights, but left the wiring harness. Now, I can use those wires to simply plug into the lights individually without needing to use vampire clips, t-taps, or whatever you want to call the lazy-man's splice.

### Relay basics and overview of the circuit
The wiring harness is protected by a relay and 10A fuse. In this diagram we have the 4 main terminals of the relay:
- 87 - Switched power to the lights
- 86 - Main ground
- 85 - Switch power relay circuit
- 30 - Main power

Here's a quick rundown of how a relay would work.

A relay is basically two switches in one. We have our low power switch, which is our on/off button powered by the VDO gauges, going to the relay. When we turn the switch to the ON position, we complete the circuit from the VDO gauge and send power to the relay. Next, we have our high power switch. 

Once the high side receives enough electrical current, the relay will allow the main power to flow to the headlights, powering the headlights and completing the circuit.

This is all to protect the two circuits from needing to use the same amount of current. Similar to the difference between powering a lightbulb and powering a refrigerator, you use the same power from your house, but run them along different circuits to protect the smaller cirucit.

### Hooking up the wires, it's... mostly straightforward

From ground to power, complete the circuit. This is how you can understand wiring.

Draw yourself a diagram if you're planning on doing something similar and see where power goes, from ground to positive, understanding where and when power flows through. This helps when you're trying to splice into a circuit. Splice into the ground to retrieve a ground point, now, where does my cirucit get power from? Does my circuit give power and switch power? Where does power come from? The battery?

Most of our bonehead aftermarket solutions tap into a circuit that turns on from Ignition On. Finding ignition on what some people get intimidate about. The first time I heard that, I had no idea what I was looking for.

#### Part 1/3 - Add your new toggle switch, the low power side

Ignition on circuits are just that, the circuit is complete when you turn your car to the ON (not to the start) position. **In most cases, it's your gauges, switches, or radio. Don't forget your cigarette lighter!** The biggest giveaways are to figure out what is the general color for grounds for your car. For these older VWs, it's brown. That is likely your ground wire. 

Once you find a circuit, you can use a multimeter for testing. You're goal is to determine what wires are power and ground. Switch your multimeter to measure voltage (V), up to the tens digit. Find a probable ground to test our wires with. Look in your car and look for bare metal, or something that looks like unpainted chassis. In my case, the metal near the parking brake. Take one probe and put touch it there, this is also called grounding your wire. I used the black one to represent the ground 

Next, take your other probe and touch the wire or terminal that is probably ignition on power, alligator clips would help but aren't necessary. Read your voltmeter, it should say 0. This is our testing probe.

Insert the key and turn the car to the ON position.

Ground one probe, test with the other probe. Did your voltmeter change voltage? It should change to 12V. If not, then that wire or terminal is not a powered circuit. Try another one. It shouldn't take too long to figure out which wire it is.

Once you've confirmed your power source, tap into it and don't forget to cover it with tape or heat shrink. Run this tap to your toggle switch. The other terminal will run towards the 85 of our relay. You may have a third wire for power to the indicator light on the switch, run another wire to this to give it power for the light. 

Good, 1/3 of wiring is done.

#### Part 2/3 - Routing to the new lights, the high power side

You should have your new wires from the cabin routed through the firewall, if not... go do that. Label the wires. Don't connect the wires to your relay yet.

Let's look at the main power and main ground of the relay. 

On your relay, find terminal 30 and run a wire from terminal 30 to battery (+). This is the main power to the relay.
Then, run a wire from terminal 86 to the body, but do not connect it to your relya yet. Clean up the body ground with a wire brush and fasten it down. This is the main ground to the relay. Leave the main ground disconnected.

Lastly, terminal 87 will be run to your new headlights. We are splitting the wire in two, one wire to each highlight circuit. You can simply strip the wire down enough to wrap to wires around, then cover it with solder and electrical tape. Connect these to the positive terminal of the headlight. 

From the headlights, run a wire from the negative terminal to the body. You can choose to combine the wire into one or make two holes in the chassis. It's cleaner if you can combine and tuck them away in the same place. But it's your shitbox, do what you like.

That's all the wires, so what's part 3/3?

#### Part 3/3 - Mounting, taping, and cleaning up wires

For good wiring practice, mounting your relay in a nice place, tape up your wires together with Tesa fabric tape and loom it together. Zip ties would be good to fasten things down along the bay. At this point, you may find loose crimps, bad wiring jobs, or may have acciendtally shocked yourself. When you're finally done, connect your toggle switch terminal 85, headlight power 87, confirm main power terminal 30, and lastly connnect your main ground terminal 86. If all goes well, you should have new working lights.  


It was confusing at first, but after walking through the diagram, and even testing it with a spare motorcycle battery, you can start to understand the process.




What wire? General rules of thumb, 12 AWG for boy power, 18 AWG for the rest. BUT, refer to a wiring chart on your choice of wire. Household Home Depot wire will work, but get some real copper at places like wirebarn.com. 

### Installation, finally.
0. Double check your wiring diagram and loosely map your wires.
1. Remove the gril using a philips head screwdriver, or whatever fastener the person used before you. Be gentle with the plastic clips. 
2. Install the new grill
3. Install the fog lights, inner lights, whatever you want to call them. If you're going the route of custom mounting points, you may use 5.25" lights to fit into the quad grill, you'll have to figure out a way to fasten it, though.
4. Install your wires. Work from the cabin to the engine bay, feeding your wires through the firewall.
5. Install your wires to positive and ground
6. Check your grounds and test. Clean grounds are the beginning and end of most electrical issues.
7.


Find my (very) periodic posts here. Or something.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
