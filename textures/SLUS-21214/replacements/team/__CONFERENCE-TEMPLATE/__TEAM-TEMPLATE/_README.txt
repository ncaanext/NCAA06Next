In this team folder there should be a folder that corresponds to every in-game uniform slot (Home, Away, Alternate #1, etc.). An alternate uniform slot can be used for something as simple as a change to one piece of the uniform, such as a different helmet or pants, or the slot can be used for an entirely different uniform. NOTE: As of NCAA NEXT V12, alternate slots can only be used to change the pieces of the uniform as was originally defined in the base game. This is often only one piece of the uniform, sometimes more, but it varies from team to team and slot to slot.

Only put textures in those folders that are specific to that slot. Do not put textures in those folders if they are shared with any other uniform slots.

All textures that are shared across two or more uniform slots should go into the _general folder. For example, the helmet, pants, socks, or cleats might go in here if they are not specific to one uniform slot. All player equipment replacement textures should go in the general folder (wristbands, sleeves, etc).

If a texture in the general folder is not shared among all slots, add the slots to the folder name to specify where they are used. For example, if a team uses the same pants across all uniform slots except Alt #1 and Alt #2, the general folder would have two folders for the helmet, named as such:

-_general
---helmet
---helmet-alt1&2

If the helmet folder (or socks, etc.) is in the general folder, delete the unused helmet folder in the Home, Away, etc. folders.

As a reminder, always make sure that no two files have the same file name. File names must be unique across the entire replacements folder.

Final note: when creating alternate uniforms, note that all odd number Alternate slots (1, 3, etc.) are dark uniforms (home uniforms is 99% of cases). All even numbers (2, 4, etc.) are light uniforms. The game will only allow a matchup between a dark uniform and a light uniform, never dark vs dark or light vs light.

