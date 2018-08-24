# xxproject
xx脚本仓库
测试用例
function BattleScene:init()
    local uiLayer = cc.Layer:create()
    local battleLayer = cc.Layer:create()
    self:addChild(battleLayer)
    self:addChild(uiLayer)
    self.uiLayer = uiLayer
    self.battleLayer = battleLayer
    self.memoryLabel = self:createBottomLable()
    self:enableNodeEvents()
end