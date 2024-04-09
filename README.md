if getgenv().thunderclient then return end

repeat task.wait() until game:IsLoaded()
task.wait(1)

getgenv().thunderclient = true
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/verified/dca3e69649ed196af0ac6577f743a0ae.lua"))()
