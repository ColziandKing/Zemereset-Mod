# Memereset-Mod
A Star Wars mod for Unciv. With help from Sullien, and it works well with his Jedi Order and our Galactic Empire. This Underworld mod has mercenaries and smugglers, create your own criminal dynasty. "Starting tech"elephant


	// Solid
	{
		"name": "Revolution",
		"era": "Future era",
		"uniques": [
			"Comment [Obsolete with [Civ V Brave New World]]",
			"Unavailable",
			"Will not be displayed in Civilopedia",
			"[-100]% weight to this choice for AI decisions",
			"[Great Artist] is earned [25]% faster",
			"[Great Musician] is earned [25]% faster",
			"[Great Writer] is earned [25]% faster",
		 "Adopt [Cultural Centers]",
			"Get the leader title of [Master/Mistress [leaderName]]",
			"[-50]% weight to this choice for AI decisions <when [Cultural] Victory is disabled>"
		],
		"priorities": {
			"Neutral": 0,
			"Cultural": 60,
			"Diplomatic": 10,
			"Domination": 10,
			"Scientific": 10
		},
		"civilopediaText": [
			{ "text": "[Aesthetics] improves the civilization's ability to generate [Culture]." }
		],
		"policies": [
			{
				"name": "Pluralism",
				"uniques": [
				"Comment [Starts with [Autocracy] adopted]",
				"Adopt [Autocracy] <hidden from users>",
				"Comment [Starts with [Order] adopted]",
				"Adopt [Order] <hidden from users>",
				"Comment [Starts with [Freedom] adopted]",
				"Adopt [Freedom] <hidden from users>",
					"[+1 Science] per every [4] [Faith] <starting from the [Modern era]>",
					"[+1 Gold, +1 Production] per every [5] [Faith] <starting from the [Modern era]>",
					"[+2 Food] from each Trade Route","[-25]% Food consumption by specialists [in all cities]"
				],
				"row": 2,
				"column": 3
			},
			{
				"name": "Revolution Complete",
				"uniques": [ 
					"Will not be displayed in Civilopedia"
				]
			}
		]
	},	      

			"[-10]% Strength <for [All] units> <for [10] turns> <upon being defeated>",
			"Gain [-50] [Science] <(modified by game speed)> <upon being defeated> <hidden from users>",
			"Gain [-50] [Culture] <(modified by game speed)> <upon being defeated> <hidden from users>",
			"Gain [-100] [Gold] <(modified by game speed)> <upon being defeated> <hidden from users>",
			"Comment [Lose [-50 Culture, -50 Science, -100 Gold] upon being defeated]"
			"Limited to [1] per Civilization",
[
	{
		"name": "Choice of Assistance",
		"text": "Tyranny, Liberty, or Conformity?",
		"presentation": "Alert",
		"choices": [
			{
				"text": "Tyranny",
				"uniques": [
					"Free [Lancer] appears","Adopt [Pluralism]",
					"[+40]% weight to this choice for AI decisions"
				]
			},
			{
				"text": "Liberty",
				"uniques": [
					"Free [Knight] appears","Adopt [Dual Crown Authority]",
					"[+20]% weight to this choice for AI decisions"
				]
			},
			{
				"text": "Conformity",
				"uniques": [
					"Free [Cavalry] appears","Adopt [Mutual Aid]",
					"[+60]% weight to this choice for AI decisions"
				]
			}
		]
	},
]
"[+3 Happiness, +4 Production] [in all cities] <after adopting [Voluntarism]>"
"[+20]% growth [in all cities] <after adopting [Voluntarism]>"
"Gain control over [All] tiles in a [1]-tile radius <upon building a [Great Improvement] improvement> <in this city> <after adopting [Voluntarism]>"
            {
                "name": "Pluralism",
                "uniques": [
				"Comment [Starts with [Autocracy] adopted]",
				"Adopt [Autocracy] <hidden from users>",
				"Comment [Starts with [Order] adopted]",
				"Adopt [Order] <hidden from users>",
				"Comment [Starts with [Freedom] adopted]",
				"Adopt [Freedom] <hidden from users>",
				"[Great Engineer] is earned [+50]% faster",
				"[-1 Happiness] <before the [Modern era]>",
					"Only available <before adopting [Dual Crown Authority]> <hidden from users>",
					"Only available <before adopting [Mutual Aid]> <hidden from users>",
					"Only available <before adopting [Pluralism]> <hidden from users>",
                ],
                "row": 3,
                "column": 9
            },
            {
                "name": "Mutual Aid",
                "uniques": [
					"[+25]% of excess happiness converted to [Production] <in [in all cities connected to capital] cities>",
					"Rebel units may spawn <when below [0] [Happiness]>",
					"[+1 Production] from all [Production] buildings <after discovering [Replaceable Parts]>", 
					"[+2 Production] from [Manufactory] tiles [in all cities] <within [1] tiles of a [City center]>",,
					"[+4] HP when healing <after adopting [Tradition Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Liberty Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Honor Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Piety Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Patronage Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Commerce Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Order Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Autocracy Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Freedom Complete]> <hidden from users>",,
	"[+4] HP when healing <after adopting [Aesthetics Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Exploration Complete]> <hidden from users>",
	"[+4] HP when healing <after adopting [Rationalism Complete]> <hidden from users>"
					"Only available <before adopting [Mutual Aid]> <hidden from users>",
					"Only available <before adopting [Pluralism]> <hidden from users>",
					"Only available <before adopting [Dual Crown Authority]> <hidden from users>",
                ],
                "row": 2,
                "column": 9
            },
            {
                "name": "Dual Crown Authority",
                "uniques": ["Comment [Provides a [Palace] in your first [2] cities for free (Your second city also becomes a capital)]", 
					"Provides a [Palace] in your first [2] cities for free <hidden from users>",
					"[+1 Science] per [3] social policies adopted",
					"[+2 Production, +2 Culture, +2 Happiness] [in all cities] <in cities with at least [4] [Specialists]>", 
					"Only available <before adopting [Dual Crown Authority]> <hidden from users>",
					"Only available <before adopting [Mutual Aid]> <hidden from users>",
					"Only available <before adopting [Pluralism]> <hidden from users>",
                ],
                "row": 1,
                "column": 9
            },
{
	"name": "Union",
	"adjective": ["American"],
	"leaderName": "Abraham Lincoln",
	"preferredVictoryType": "Domination",
	"favoredReligion": "Christianity",

	"declaringWar": "The United States hereby declares war. May God have mercy on your nation, for we shall not!",
	"attacked": "Every inch of American soil will be defended with the full might of our great nation. Prepare for a war you cannot win!",
	"defeated": "Though our great republic falls today, the spirit of American resilience can never be truly conquered. The foundation of democracy can never be shook!",
	"introduction": "I am Abraham Lincoln, President of the United States of America. Our nation stands ready to transform the world through bold action and unwavering resolve. The strenuous life awaits!",

	"neutralHello": "Greetings, leader.",
	"hateHello": "Your weakness is apparent.",

	"tradeRequest": "Let us discuss terms that advance our respective national objectives.",

	"outerColor": [22, 16, 50],
	"innerColor": [255, 255, 255],

	"uniqueName": "The Perfect Union",
	"uniques": [
		"Adopt [Constitution]",
	"[+1 Culture, +2 Science] from all [Wonder] buildings",
	"[+2 Culture, +2 Science] from every [Natural wonder]",
	"May buy [Governor Mansion] buildings for [120] [Culture] [in all cities] at an increasing price ([140])",
	"Comment [[-5]% Culture cost of adopting new Policies for every 2 [Governor Mansion] buildings constructed with up to -40%]",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [2] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [4] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [6] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [8] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [10] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [12] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [14] of [in all cities] cities> <hidden from users>",
	"[-5]% Culture cost of adopting new Policies <if [Governor Mansion] is constructed in at least [16] of [in all cities] cities> <hidden from users>",
],

	"spyNames": ["James", "Robert", "John", "William", "Richard", "David", "Charles", "Thomas", "Michael", "Ronald"],
	"cities": ["Washington D.C", "New York City", "Los Angeles", "Chicago", "Detroit", "San Francisco", "Philadelphia", "Boston", "Seattle", "New Orleans", "Richmond", "Baltimore", "Cleveland", "Pittsburgh", "Milwaukee", "Minneapolis", "St. Louis", "Oakland", "Atlanta", "Indianapolis", "Tucson", "Denver", "Kansas City", "Portland", "Fresno"],
},
	{
		"name": "Pura",
		"replaces": "Temple",
		"uniqueTo": "Majapahit",
		"cost": 70,
		"hurryCostModifier": 160,
		"faith": 2,
		"requiredBuilding": "Shrine",
		"civilopediaText": [ {"text": "Hinduism was the first major global religion to reach Indonesia, arriving with the wave of Sanskrit and other South Asian influences in the first century AD. Hinduism spread via the poetry and epics of Sanskrit literature, and local rulers sought power by linking themselves via the religion to distant (and prestigious) centers in South Asia. Once settled in the palace, the religion slowly filtered down to the rest of the population. We see the construction of Hindu temples steadily from the first millennium onward, including the structures at Borobudur, Prambanan, and elsewhere. Building temples became a language of power for Majapahit elites, one they took with them as they fled their declining empire to the island of Bali. \nFrom Bali, we take the term 'pura'. Hindu temples in Java, where the Majapahit Empire was based, are still referred to as candi, but here we use the Balinese term to avoid confusion with the candi bentar building as well as mark the Majapahit legacy of the island."}, {"separator": true}],
		"uniques": ["[-15]% Food consumption by [Specialists] [in this city]", "Destroyed when the city is captured"],
		"requiredTech": "Philosophy"
	},
	{
		"name": "Necropolis",
		"replaces": "Temple",
		"uniqueTo": "Khemet",
		"cost": 100,
		"hurryCostModifier": 160,
		"faith": 2,
		"requiredBuilding": "Shrine",
		"civilopediaText": [ {"text": "According to ancient Egyptians, true immortality was found in death, but significant preparation was required to achieve the best outcome in the afterlife. The necropolis ('city of the dead') developed to support and serve the extensive funerary practices that prepared body and soul for their final journey. Upon death, Egyptians believed the soul departed the body, which needed to be preserved until the spirit’s return allowed for rebirth. This process was accomplished through mummification, during which the organs were removed and the corpse was dried out, treated, and wrapped in linen before being interred in a sarcophagus. The dead were buried with spells to guide them to the afterlife, as well as food, tools, treasures, and other supplies they would need for the journey. \nNumerous dangerous paths traversed the Duat, or underworld, and the passage taken by the deceased was determined by their status in life. If the soul succeeded in this voyage, it faced judgment and was weighed against the feather of Ma’at to determine if it was pure enough to enter Sekhet-Aaru, the paradisial Field of Reeds. Those who passed the test would find new life…those who failed were consumed by the goddess Ammit, never to be reborn."}, {"separator": true}],
		"uniques": ["Gain [100] [Gold] <upon constructing [Wonders] [in this city]> <(modified by game speed)>", "Destroyed when the city is captured"],
		"requiredTech": "Philosophy"
	},


	 {
        "name": "Madinat",
        "maintenance": 2,
		"replaces": "University",
		"uniqueTo": "The Abbasids",
		"cost": 160,
		"hurryCostModifier": 160,
        "percentStatBonus": {"science": 33},
        "specialistSlots": {"Scientist": 2},
        "requiredBuilding": "Library",
		"civilopediaText": [ {"text": "Religion and education were closely intertwined under Abbasid rule, and the pursuit of knowledge was considered a key part of one’s spiritual journey. Early schooling focused on memorizing and studying religious texts. The development of the madrasa presented the opportunity for higher education and entry into the ranks of the ulema (the plural form of ʿālim), a community of scholars whose expertise on matters of legal import was invaluable to the empire. The mosque’s role as the center of spiritual and communal life formed a natural bond with the madrasa’s focus on religious-based scholarship, and the two buildings were typically constructed in a single complex that included a library and a boarding house for students, funded through charitable donations."}, {"separator": true}],
        "uniques": ["[+2 Science] from [Jungle] tiles [in this city]","[+2 Science, +1 Gold] from every specialist [in this city]"],
        "requiredTech": "Education"
    },
