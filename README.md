# Memereset-Mod
A Star Wars mod for Unciv. With help from Sullien, and it works well with his Jedi Order and our Galactic Empire. This Underworld mod has mercenaries and smugglers, create your own criminal dynasty. "Starting tech"

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
