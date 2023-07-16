# magnifica-stats
The various brew strengths that the Magnifica ESAM 3300 can produce

I, like many others, own a DeLonghi Magnifica ESAM 3300. It's a great little machine. It's certainly the cheapest machine I've been able to find that has two boilers, a decent steam wand, and produces plenty of pressure for espresso, but without any of the frills.

HOWEVER, there is one GLARING flaw. And that's that the stupid little dosing knobs have no concrete measurements, only "more" and "less", for coffee and water.

And on top of that, I couldn't find any measurements online to fill in these gaps. So I am going to measure for each setting indicator (the little dots on the dials) the amount of (dry) coffee in, the amount of liquid out, and the ratio.

## Coffee measurements

To measure the amount of dry coffee, I weigh the grounds bin, then press the coffee button, and immediately after the coffee is tamped (before the pre-infusion starts), click the coffee button again to cancel, wait for the machine to spit the grounds into the grounds bin, and weigh it again. The difference in weight is the amount of coffee the machine intended to use. I typically take a few measurements and average them. I haven't yet bothered to report the standard deviation of these averages, though I really should.

NOTE: Coffee measurements are counted from 0 (maximum)

| **Amount setting** | **Shot button (single/double)** | **Coffee weight (grams)** |
|--------------------|---------------------------------|---------------------------|
| 0 (Max)      | Single                          | 11.2                      |
| 0 (Max)      | Double                          | 15.4                      |
| 1     | Single                          | 11.0                      |
| 1      | Double                          | 14.9                      |
| 2     | Single                          | 10.9                      |
| 2      | Double                          | 14.5                      |
| 3    | Single                          | 10.1                      |
| 3     | Double                          | 13.9                      |
| 4  | Single                          | 9.9                      |
| 4      | Double                          | 12.2                      |
| 5      | Single                          | 9.3                      |
| 5     | Double                          | 11.9                      |
| 6     | Single                          | 8.6                      |
| 6     | Double                          | 11.8                      |
| 7      | Single                          | 8.2                      |
| 7      | Double                          | 11.6                      |
| 8      | Single                          | 7.5                      |
| 8      | Double                          | 11.0                      |
| 9     | Single                          | 7.1                      |
| 9      | Double                          | 10.7                      |
| 10     | Single                          | 6.0                      |
| 10     | Double                          | 10.5                      |
| 11 (Min)    | Single                          | 5.8                      |
| 11 (Min)     | Double                          | 10.1                      |
|                    |                                 |                           |

## Liquid measurements
To measure coffee liquid output, I simply brew onto a 0.1-gram accurate kitchen scale.

NOTE: Liquid measurements are counted from 0 (minimum)

| **Amount setting** | **Shot button (single/double)** | **Output Liquid weight (grams)** |
|--------------------|---------------------------------|----------------------------------|
| 0 (Far left)       | Single                          | 14.6                             |
| 0 (Far left)       | Double                          | 30.2                             |
| 1                  | Single                          | 25.8                             |
| 1                  | Double                          | 52.4                             |


## Ratio measurements

Here is a summary of how these stats relate to each other, along with the brew ratio

Since these are analog dials, to get a ratio between any of these data points, you can of course set the dials between the two dots that are closest to what you are aiming for.

| **Amount setting (Coffee)** | **Amount setting (Water)** | **Shot button (single/double)** | **Output Liquid weight (grams)** | **Input Coffee weight (grams)** | **Brew Ratio** | **Category** |
|-----------------------------|----------------------------|---------------------------------|----------------------------------|---------------------------------|----------------|--------------|
| 0 (Far right)               | 0 (Far left)               | Single                          | 14.6                             | 11.2                            | 1.30:1         | Ristretto    |
| 0 (Far right)               | 0 (Far left)               | Double                          | 30.2                             | 15.4                            | 1.96:1         | Espresso     |
| 0 (Far right)               | 1                          | Single                          | 25.8                             | 11.2                            | 2.30:1         | Espresso     |
| 0 (Far right)               | 1                          | Double                          | 52.4                             | 15.4                            | 3.40:1         | Lungo        |

Over time, I plan to fully populate this table.


## Takeaways

- The coffee input weight is not very precise. I think the machine is only accurate to about +/- one gram. That's not really the level of accuracy that we may be aiming for.
- Some coffee doesn't end up in the brew system and instead ends up on the floor of the machine. Perhaps that's where some of the variablility comes from.
