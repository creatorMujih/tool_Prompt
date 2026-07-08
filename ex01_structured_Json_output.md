## Write a prompt that asks for unstructured information (e.g., “List three cities with their populations.”).

P**Prompt:** mention 4 african countries, their capitals, name of their president and colours of flag.

**Output:**
 Here are four African countries with their capitals, current presidents, and flag colors:

1. **Nigeria**
   * Capital: Abuja
   * President: Bola Tinubu
   * Flag colors: Green, White

2. **Kenya**
   * Capital: Nairobi
   * President: William Ruto
   * Flag colors: Black, Red, Green, White

3. **Egypt**
   * Capital: Cairo
   * President: Abdel Fattah el-Sisi
   * Flag colors: Red, White, Black, Gold

4. **South Africa**
   * Capital (administrative): Pretoria
   * President: Cyril Ramaphosa
   * Flag colors: Black, Green, Yellow, White, Red, Blue


## Rewrite the prompt to enforce structured JSON output:
**Example: “Return the following in JSON format: [{city: string, population: number}].”**

**Prompt:**
mention 4 african countries, their capitals, names of their president and colours of flag and return it in the JSON format.

**Output:**
[
{
"country": "Nigeria",
"capital": "Abuja",
"president": "Bola Tinubu",
"flag_colors": ["Green", "White"]
},
{
"country": "Kenya",
"capital": "Nairobi",
"president": "William Ruto",
"flag_colors": ["Black", "Red", "Green", "White"]
},
{
"country": "Egypt",
"capital": "Cairo",
"president": "Abdel Fattah el-Sisi",
"flag_colors": ["Red", "White", "Black", "Gold"]
},
{
"country": "South Africa",
"capital": "Pretoria",
"president": "Cyril Ramaphosa",
"flag_colors": ["Black", "Green", "Yellow", "White", "Red", "Blue"]
}
]

**More input:**

**Prompt:** list 2 countries with their staple foods

**Output:**
1. Japan – Rice
2. Mexico – Maize (corn)

**Prompt**
list 2 countries with their staple foods and provide answer in the JSON format.

**Output**
JSON:
[
{
"country": "Japan",
"staple_food": "Rice"
},
{
"country": "Mexico",
"staple_food": "Maize (corn)"
}
]



## Test with multiple inputs and verify the JSON stays valid.
Yes, the JSON stays valid.

