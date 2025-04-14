local settings = {
    SaveDecompileLogs = false,
    SaveScanLogs = false,
    ScanForNewInstance = false,
    InterceptUntilRan = false,
    CursorOffset = -15, -- Cursor offset
    PathToDump = {game.Players.LocalPlayer, game:GetService('ReplicatedStorage')}

}
_G.data = settings
loadstring(game:HttpGet('https://raw.githubusercontent.com/ScriptSkiddie69/RemoteHook/refs/heads/main/SimpleSpyLite.lua'))()
