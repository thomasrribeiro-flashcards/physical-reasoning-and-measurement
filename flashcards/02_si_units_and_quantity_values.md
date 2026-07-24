+++
order = 2
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "si-units", "unit-prefixes", "quantity-values", "unit-conversion"]
prerequisites = ["chapter:01_systems_quantities_and_models"]
provides = [
  "si",
  "si-base-unit",
  "unit-symbol",
  "quantity-symbol",
  "unit-prefix",
  "micro-prefix",
  "mega-prefix",
  "prefix-conversion",
  "unit-notation-rules",
]
+++

# SI units and quantity values

## One agreed system

<!-- card-id: 5a1c2f76-9c1e-4a6f-8f2d-3b8a4c9e6d01 -->
Q: Measurements are only comparable when everyone uses the same agreed units. The **International System of Units** — abbreviated **SI** — is the worldwide framework that supplies them. It begins with seven **base units**, independent reference units from which the rest of the SI is built. For length the base unit is the meter (m), for mass the kilogram (kg), and for time the second (s); the other four enter when their kinds of quantity are introduced later. The centimeter and kilometer are also internationally agreed length units. What makes the meter, and not these, the *base* unit of length?
A: The meter is the one fixed reference for length in the SI. The centimeter and kilometer are not independent references: each is the meter renamed by a prefix — a fixed fraction or multiple of it — so every SI length unit traces back to the meter. "Base" means the single starting unit, not merely an agreed one.

<!-- card-id: 3f7e9b24-6d15-4c88-b1a7-92c4e5f0a812 -->
Q: The marks m, kg, s, cm, and km are **unit symbols**: internationally fixed pieces of writing, identical in every country and language. A unit symbol is not an abbreviation, so it is never altered the way words are — it never takes a plural ending and never ends with a period (unless the sentence does). A road sign reads: "Next fuel 12 kms. ahead." Name the two ways this breaks the unit-symbol rules.
A: It pluralizes the symbol and adds a period. The symbol for kilometer is exactly `km` — twelve kilometers is written 12 km, with no added `s` and no period. Symbols are fixed marks, so nothing may be appended to them.

<!-- card-id: 8c4d1e57-2b9f-4f31-a6c8-70d5b3e9f423 -->
Q: A recorded quantity often looks like \(t = 30\text{ s}\). The two letters play different roles. The letter \(t\) is a **quantity symbol**: a variable the writer chose to stand for the quantity being discussed (here, a duration), and the writer could have picked another letter. The letter s is a unit symbol. In the record \(h = 1.2\text{ m}\), which symbol could the writer freely rename without changing the meaning, and which is internationally fixed?
A: The quantity symbol \(h\) is the writer's choice — calling the height \(x\) or \(a\) instead would change nothing, provided the choice is stated. The unit symbol m is fixed by the SI: no other mark means "meter." One symbol belongs to the writer, the other to the worldwide agreement.

## Reading a quantity value

<!-- card-id: 6b2a8f93-4e07-4d52-9c31-e8a67d04b5c9 -->
Q: A quantity value is a number together with a unit — and the pairing is exactly a multiplication: \(40\text{ cm}\) means \(40 \times (1\text{ cm})\), forty copies of the centimeter laid end to end, just as measuring with a repeated unit counts copies. Because the value is "number times unit," the two parts are written as separate factors, with a space between the number and the unit symbol: 40 cm, not 40cm. In the value \(2.5\text{ km}\), what exactly does the 2.5 count?
A: Copies of the kilometer: \(2.5\text{ km} = 2.5 \times (1\text{ km})\) — two and a half kilometer-lengths laid end to end. The number by itself counts nothing; it only says *how many of the stated unit*.

<!-- card-id: 9d5f3a68-1c74-4e29-b8d2-56a9c1e7f034 -->
Q: Chapter 1 established that \(40\text{ cm}\) and \(0.40\text{ m}\) report the same length. The number-times-unit reading shows *why* the quantity itself cannot change during conversion. Write \(40\text{ cm} = 40 \times (1\text{ cm})\), use the exact relation \(1\text{ cm} = 0.01\text{ m}\), and substitute it: \(40 \times 0.01\text{ m} = 0.40\text{ m}\). Why does this substitution guarantee that the underlying quantity is untouched?
A: Every step replaces one expression with an exactly equal one: 1 cm *is* 0.01 m, so swapping them changes only the written form, never the length being described. Converting a value is substitution into a product — arithmetic on the report, not an operation on the object.

## Prefixes

<!-- card-id: 2e8b6c41-9a53-4d17-8f4e-b1c09d72a685 -->
Q: The renaming syllables already met — centi- (one hundredth), kilo- (one thousand), milli- (one thousandth) — are **prefixes**. A prefix attached to the front of a unit name multiplies that unit by its one fixed factor, creating a new unit of the same kind; and the new unit's symbol is simply the prefix symbol joined to the unit symbol: c + m gives cm, m + L gives mL. The same prefix, with the same factor, works on any SI unit. Attach milli- to the meter: name the resulting unit, its symbol, and its exact relation to the meter.
A: The millimeter, symbol mm — one thousandth of a meter, so \(1\text{ mm} = 0.001\text{ m}\) and \(1000\text{ mm} = 1\text{ m}\). Milli- carries its factor with it: it means one thousandth no matter which unit it is attached to.

<!-- card-id: 7f1c5d29-8b46-4a90-93e5-c62d8f4b7e16 -->
Q: Two more prefixes extend the ladder beyond kilo- and milli-. **Micro-**, symbol µ, multiplies a unit by one millionth (0.000001) — a human hair is roughly 70 µm across. **Mega-**, symbol M, multiplies a unit by one million (1 000 000). Using the stated factors, which is the longer length, 1 µm or 1 mm — and exactly how many of the shorter one make the longer one?
A: The millimeter is longer: 1 mm is one thousandth of a meter while 1 µm is only one millionth, so one thousand micrometers make one millimeter (a thousand thousandths of a thousandth make a thousandth). The hair benchmark agrees: about 70 µm is well under a tenth of a millimeter.

<!-- card-id: 4a9e7b35-5f28-4c61-a7d9-83f1b6c04e57 -->
C: One **micrometer** (µm) is one [millionth] of a meter — a human hair is roughly seventy micrometers across.

<!-- card-id: 1d6c4f82-3e91-4b57-86a3-f74d29e8b5a0 -->
C: One **megagram** (Mg) is one [million] grams — about the mass of a small car.

<!-- card-id: 5e3a9d17-7c64-4f28-b9e1-04a8c5f36d72 -->
Q: Prefix and unit symbols are **case-sensitive**: a capital letter and a small letter are different symbols with different fixed meanings, and nothing else in the writing distinguishes them. The small m as a prefix means milli-; the capital M means mega-. A pharmacy label reads 5 mg and a freight form reads 5 Mg. How different are these two masses?
A: Enormously — 5 mg is five thousandths of a gram, a speck-sized dose, while 5 Mg is five million grams, that is 5000 kg, the mass of several cars. One letter's case is the only written difference, which is why Kg, KM, and other case changes are not harmless style but different (or meaningless) symbols.

<!-- card-id: 0b8f2c64-9d17-4e83-a5f6-31c7e9d24b08 -->
Q: The SI base unit of mass is the kilogram — the only base unit whose *name already contains a prefix* (kilo- on the gram). To keep names readable, prefixes are never stacked: a new prefix attaches to the plain word gram, never to "kilogram." A lab needs a unit name for one thousandth of a kilogram. Why is "millikilogram" wrong, and which existing unit is it?
A: Stacking milli- onto kilogram is forbidden — prefixes attach to gram. One thousandth of a kilogram already has a name: the gram itself, since \(1\text{ kg} = 1000\text{ g}\) means \(0.001\text{ kg} = 1\text{ g}\). Smaller mass units continue from the gram: mg, µg.

<!-- card-id: 6f4b8e21-2a75-4d93-b8c4-59e0a7f13c86 -->
Q: A prefix is usually chosen so the number in the value stays easy to read — as a rule of thumb, somewhere between 0.1 and 1000. A machine screw's length is recorded as \(0.004\text{ m}\). Rewrite this value with a prefixed meter unit so that the number is a whole number between 1 and 999. Which value results?
A: With the millimeter it is \(4\text{ mm}\), since \(0.004\text{ m} = 4 \times 0.001\text{ m}\). The length is unchanged — only the unit and its matching number moved. (Writing 0.4 cm is equally correct but keeps a decimal, so mm is the choice that meets the stated whole-number request.)

## Converting along the ladder

<!-- card-id: 3c7d5a94-6e18-4f26-91b7-d85c2e4a6f39 -->
Q: The figure lines up four length units as a ladder from smallest to largest, and each connector states the exact relation between neighbors.

![A ladder of four length units in a row from smallest to largest: millimeter, centimeter, meter, kilometer. Connectors between neighbors state that one centimeter is ten millimeters, one meter is one hundred centimeters, and one kilometer is one thousand meters.](../figures/02_si_units_and_quantity_values/prefix-ladder.svg)

A length is recorded in centimeters and must be re-expressed in kilometers. Using the ladder, state the operation for each step and the single overall factor that results.
A: Divide twice: by 100 from cm to m, then by 1000 from m to km — an overall division by 100 000. Moving toward a larger unit always divides, because fewer copies of a bigger unit cover the same length; the ladder supplies the factors, and composing steps multiplies them: \(100 \times 1000 = 100\,000\).

<!-- card-id: 8a2f6d48-1b93-4e57-a2c6-70f4b8d15e93 -->
P: A running trail is \(2.4\text{ km}\) long. Express its length in centimeters, converting through the base unit.
S: **IDENTIFY:** One length, one quantity — only its written unit changes, from kilometers to centimeters. No single km–cm relation has been memorized, but both units connect to the meter: \(1\text{ km} = 1000\text{ m}\) and \(1\text{ m} = 100\text{ cm}\).

**PLAN:** Convert in two substitution steps through the meter: replace the kilometer by 1000 m, then replace each meter by 100 cm. Both steps move toward a smaller unit, so both multiply.

**EXECUTE:** The trail is \(240\,000\text{ cm}\) long: \(2.4\text{ km} = 2.4 \times 1000\text{ m} = 2400\text{ m}\), and \(2400\text{ m} = 2400 \times 100\text{ cm} = 240\,000\text{ cm}\).

**EVALUATE:** Direction check: centimeters are far smaller than kilometers, so the number must grow — it did. Factor check: the two steps compose to \(1000 \times 100 = 100\,000\) cm per km, and \(2.4 \times 100\,000 = 240\,000\). The quantity itself never changed; only equal expressions were substituted.

<!-- card-id: 9e6b3f75-4d21-4a68-b5e9-16c8d2a7f450 -->
P: A spool holds \(52\,000\text{ cm}\) of cable. Express the cable's length in kilometers.
S: **EXECUTE:** The cable is \(0.52\text{ km}\) long: \(52\,000\text{ cm} \div 100 = 520\text{ m}\), and \(520\text{ m} \div 1000 = 0.52\text{ km}\).

**EVALUATE:** Both steps move toward a larger unit, so both divide and the number must shrink — it fell from 52 000 to 0.52. Sense check: 520 m is about half of one kilometer, and 0.52 km says exactly that.

<!-- card-id: 2d9c7e53-8f36-4b14-97a2-c45e1b8d6f27 -->
Q: SI prefixes rescale a unit by tens, hundreds, thousands — but not every familiar unit is a prefixed form. The minute and the hour are separate agreed units built on sixties: \(1\text{ min} = 60\text{ s}\), \(1\text{ h} = 60\text{ min}\). A student converts \(2.5\text{ min}\) to seconds by multiplying by 100, "because unit steps always work in tens." Diagnose the error and give the correct value.
A: The minute is not a prefixed second, so no tens-ladder factor applies: the relation is 60 s per minute, giving \(2.5 \times 60 = 150\text{ s}\). Tens-based factors belong to prefixes; the time units minute and hour keep their own sixty-based relations.

<!-- card-id: 7b5e9a26-3c84-4f19-8d67-b2a0f5c31e84 -->
P: A parts label reads: "bolt length 12mm; bolt mass 4 gs.; box mass 0.25 Kg". Find every unit-writing error, and rewrite the label correctly.
S: **IDENTIFY:** A notation audit — each entry must be checked against the unit-symbol rules: a space between number and symbol, no plural ending, no period, and exact letter case.

**PLAN:** Test the three entries against those rules one by one, then rewrite.

**EXECUTE:** The corrected label is: bolt length 12 mm; bolt mass 4 g; box mass 0.25 kg. Three errors: "12mm" is missing the space between number and symbol; "gs." pluralizes the gram symbol and adds a period; "Kg" capitalizes the k, and case changes make a different or meaningless symbol.

**EVALUATE:** Each corrected symbol is a fixed SI mark (mm, g, kg), and the magnitudes are sensible for the objects: 12 mm is about a fingernail's width — right for a bolt; 4 g is a few paper clips; 0.25 kg is a quarter of a thick textbook — plausible for a small box of bolts. A case slip the other way would fail this check instantly: a 12 Mm bolt would be twelve million meters long.
