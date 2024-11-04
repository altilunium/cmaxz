# cmaxz
weather radar map viewer

https://altilunium.github.io/cmaxz/

![image](https://github.com/user-attachments/assets/cff02f2a-ff8f-4743-9da6-2d7c9dfde982)


## cmaxz?

![image](https://github.com/user-attachments/assets/2f4f1f21-a163-4a24-964e-1d8d21e59047)

In meteorology, **CMax(Z)** (short for ["Composite Maximum Reflectivity"](https://www.bmkg.go.id/cuaca/citra-radar.bmkg)) refers to the maximum radar reflectivity observed within a vertical column of the atmosphere, typically represented in decibels of reflectivity (**dBZ**). This measure is particularly useful in identifying the most intense parts of a storm and areas of heavy precipitation.

* CMax(Z) does not reflect a specific altitude but rather shows the highest reflectivity value within the entire vertical profile above a particular location.
* Since CMax represents the highest value, it helps highlight areas with intense weather activity, such as thunderstorms or hail.
* Higher dBZ values often indicate higher precipitation rates, with values above 40-50 dBZ commonly associated with heavy rain or hail.
* CMax is especially useful in identifying severe storm cores, where intense updrafts and precipitation often lead to dangerous weather phenomena like hail, strong winds, or tornadoes. CMax(Z) is a crucial tool for forecasters and meteorologists to assess storm severity and provide warnings for areas potentially impacted by severe weather.

Weather radar imagery describes the potential intensity of rainfall detected by the weather radar. The measurement of rainfall intensity (precipitation) by the weather radar is based on the amount of radar energy reflected back by water droplets in clouds, represented by the product Reflectivity with units of dBZ (decibels). The greater the reflected energy received by the radar, the higher the dBZ value, and a higher dBZ reflectivity value indicates a higher intensity of rainfall.


| Rainfall Intensity Category | dBZ Value Range | mm/hour |
|-----------------------------|-----------------|---------|
| Light rain                  | 25 to 35        | 1 to 5  |
| Moderate rain               | 35 to 45        | 5 to 10 |
| Heavy rain                  | 45 to 55        | 10 to 20|
| Very heavy rain             | > 55            | > 20    |

**dBZ** stands for "decibels of Z," where **Z** represents the radar reflectivity factor, a measure of the density and size of hydrometeors (such as raindrops, snowflakes, or hail) in the atmosphere. The **dBZ** unit indicates the intensity of returned radar signals on a logarithmic scale.

* The **Z** in dBZ refers to the radar reflectivity factor, a value proportional to the amount of power returned to the radar. This reflectivity factor is essentially a measurement of how much of the radar’s signal is scattered back by particles in the air.
* Decibels provide a logarithmic scale, which compresses a wide range of reflectivity values. In radar meteorology, dBZ is used because it simplifies the large range of reflectivity values, making them easier to interpret. For example, a 10 dBZ increase corresponds to a tenfold increase in reflectivity.
* Reflectivity values (Z) are converted to decibels (dBZ) because this makes it possible to handle the wide variation in precipitation intensity, from light rain to extreme hail.

Reflectivity in meteorology refers to the ability of objects (like raindrops, snowflakes, or hail) to reflect radar signals. Weather radars emit electromagnetic waves that travel outward from the radar system. When these waves encounter particles in the atmosphere—such as raindrops, snowflakes, or ice—they scatter. Some of this scattered energy returns to the radar, and the strength of this "echo" or "return signal" is what we call reflectivity.

Reflectivity, represented as Z, is a measurement based on the size and concentration of particles in a given volume of air. The Z value is proportional to the sixth power of particle diameter, which means larger particles contribute disproportionately to reflectivity. Because Z values can vary widely (from small drizzle droplets to large hailstones), radar systems convert reflectivity into a logarithmic unit, dBZ (decibels of reflectivity), to compress the range and make interpretation easier. Each 10 dBZ increase represents a tenfold increase in reflectivity.

Reflectivity is influenced by several factors, including: 

* Particle Size : Larger particles like hail or heavy raindrops produce stronger reflections than smaller particles like drizzle.
* Particle Concentration : A high concentration of small particles can also produce significant reflectivity, though less so than larger particles.
* Type of Precipitation : Raindrops reflect radar waves more efficiently than snowflakes because liquid water is denser and more reflective.
* Particle Shape: The shape of the particles can affect how radar waves scatter. For instance, large raindrops flatten as they fall, which can affect reflectivity.

### Data sources
https://www.rainviewer.com/sources.html
