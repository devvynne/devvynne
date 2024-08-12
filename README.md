static void UpdatePresence()
{
    DiscordRichPresence discordPresence;
    memset(&discordPresence, 0, sizeof(discordPresence));
    discordPresence.state = "The sense that you have of your own importance and value.";
    discordPresence.details = "DIG·NI·TY / ˈdiɡnədē / noun ";
    discordPresence.startTimestamp = 1507665886;
    discordPresence.endTimestamp = 1507665886;
    discordPresence.largeImageKey = "tray_large";
    discordPresence.largeImageText = "Hello";
    discordPresence.smallImageKey = "pink-color-heart-icon-isolated-transparent-background-free-png";
    discordPresence.smallImageText = "ily";
    discordPresence.partyId = "ae488379-351d-4a4f-ad32-2b9b01c91657";
    discordPresence.partySize = 1;
    discordPresence.joinSecret = "MTI4NzM0OjFpMmhuZToxMjMxMjM= ";
    Discord_UpdatePresence(&discordPresence);
}
