---
title: The sky, explained
alt: ../fr/astronomie.html
---

# The sky, explained

For the curious: what the watch faces show and how it is computed.

## The sun

- **Height**: angle of the sun above the horizon (0° at the horizon, negative below).
- **Azimuth**: its direction. It rises due east only at the equinoxes: further north-east in summer, south-east in winter.
- **Sunrise, sunset**: the edge of the sun touches the horizon. The air bends light, so you see it slightly before it is really up.
- **Solar noon**: the sun at its highest. Rarely at 12:00 exactly (time zone, daylight saving). **Solar midnight**: at its lowest.
- **Golden hour**: sun between 0 and 6° above the horizon, warm low light.

## Twilights

After sunset, night comes in steps, depending on how far the sun is below the horizon:

| | Sun | Sky |
|---|---|---|
| Civil (blue hour) | 0 to −6° | still light |
| Nautical | −6 to −12° | first stars |
| Astronomical | −12 to −18° | almost dark |
| Full night | below −18° | dark |

The other way round in the morning. Around the June solstice, in Paris, there is no full night. Beyond the Arctic Circle: the sun never sets (polar day) or never rises (polar night).

## The moon

- **Phases**: a 29.5-day cycle. New moon (on the sun's side, invisible), crescent, first quarter, gibbous, full moon (opposite the sun), then waning. The percentage is the lit part.
- **Moonrise**: about 50 minutes later each day. The full moon rises as the sun sets.
- **Height**: the full moon is high in winter, low in summer, the opposite of the sun.
- **Southern hemisphere**: the phase is seen the other way round.

## How it is computed

- **On the watch**, from the time and your location. Nothing is sent.
- **Formulas** by astronomer Jean Meeus (*Astronomical Algorithms*), describing the apparent paths of the sun and moon.
- **Once a day** (and when your location or time zone changes), then followed every two minutes by interpolation: easy on the battery.
- **Checked** over 354 days (from Quito to Tromsø) against NASA-JPL and USNO ephemerides:

| | Accuracy |
|---|---|
| Sunrise, sunset, twilights | ± 1 min |
| Moonrise, moonset | ± 5 min |
| Height, azimuth | ± 0.1° |
| Lit part of the moon | ± 1% |
| Full, new moon | ± 15 min |

Near the poles, when the sun skims the horizon, times are less precise.
