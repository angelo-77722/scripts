https://github.com/angelo-77722/scripts.gitlocal getgenv = getgenv or function() return _G end
local genv = getgenv()

-- Configurações personalizáveis
genv.FPSKillerConfig = {
    Fly = true,           -- Deseja botão de fly?
    FPSBooster = true  -- Deseja Fps Boost?
}
loadstring(game:HttpGet("https://angelo-77722.site/angelodevour"))()
