# Napoleons-Legacy-EEM
A fork of the original Napoleon's Legacy mod by nappys-legacy which ceased development sometime in 2020. It currently combines the original mod (v0.3.2)  with ujtcelvn/Extender-anon's Ending Extension Mod to provide added content on top of HPM and the ability to play until 1956. 

Upcoming plans include completing development of the planned Germany rework, fixing various oddities from v0.3.2, and eventually adding completely new content. As well as continually integrating new applicable updates from EEM.

# Credits
- nappys-legacy, who laid the crucial groundwork for the development of Napoleon's Legacy and merging the mod with HPM
- all the anons and napoleons who helped develop and create Napoleon's Legacy
- Extender-Anon for his amazing work with EEM
- arkhometha and all the HPM contributors
- The HPM Politics & Economy Patch guy, here's hoping for a version 2
- /gsg/ for being /gsg/ and /vst/ for being /vst/

# Changelog for v0.3.3
- Updated Napoleon's Legacy to use EEM 0.5.8d (As of 6/3/2023) as a base rather than HPM 0.4.5.2. I think I caught everything but don't be surprised if there is some weirdness. I also did not port over EEM's four new provices, distributed respective pops back to the provinces they were taken from. Will consider whether these should be implemented later.
- Restored the old Bookmark Title and Description
- RUS now starts with prussian_constitutionalism, mirroring HPM's changes to other constitutional monarchies, will consider liberalizing further in a future update. It still uses its HMS Government flag.
- Removed FIN influence from the Russian OOB
- Readded removed Event 325460 "Integration of Finland"
- Removed TCA, UBD, and ABK influence from the Russian OOB for now, until they are (maybe) reintegrated
- Added Event 16001 "The Slavery Debate" back in, as without it the USA can ban slavery quickly and make the entire ACW event chain nonsense
- The decision to Annex Hawaii now dynamically adds cores for NEN or USA depending on the pops there (and who still exists/won the civil war)
- Added the "Splendid Isolation" submod. It applies to BRI and can be found under the options decisions
- Fixed the Congress of Berlin not giving Central Greece to Greece
- The Kingdom of France/French Republic now start with ruling parties when they revolt
- The Kingdom of France now starts with a Reactionary upper house
- Changed ship names in a few Naval OOBs
- NSA or SPA can take the Falangist Doctrine decision under the right conditions. The event accompanying this decsion will grant cores on Portgual if Spain wants to persue the integration of Portugal but Portugal does not exist.
- Trigger happy Austrian AIs will no longer release Bukovina as a puppet when they win the Hungarian Uprising
- The Ottomans can no longer create Transcaucasia by sphering Persia
- Restored history files for some tags that were cut in v0.3.2 for potential reimplementation later, they are not present in-game
- Tweaked the "Restore Austrian Empire" cb so it does not target Galicia or non-existent Venitian cores
- Fixed misc items in the validator

# Todo
- Implement and finish the partially completed German Rework
- Add in Elba, and EEM's four new provinces
- Fix oddities around some scripted wars (ACW, Bengal Revolt)
- Integrate the UI Recolor
- Decision/Events for France and Haiti's unresolved issues
- Look into ideas from HPMP
- Rework Argentina/United Provinces
- Further flesh out North America
- Research and implement planned content from even older versions that was never completed
