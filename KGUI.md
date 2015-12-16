# ItemNull
--------------------

[`SetVisible`](#LuaItemNull_SetVisible)
[`Show`](#LuaItemNull_Show)
[`Hide`](#LuaItemNull_Hide)
[`PtInItem`](#LuaItemNull_PtInItem)
[`SetRelX`](#LuaItemNull_SetRelX)
[`SetRelY`](#LuaItemNull_SetRelY)
[`GetRelX`](#LuaItemNull_GetRelX)
[`GetRelY`](#LuaItemNull_GetRelY)
[`SetAbsX`](#LuaItemNull_SetAbsX)
[`SetAbsY`](#LuaItemNull_SetAbsY)
[`GetAbsX`](#LuaItemNull_GetAbsX)
[`GetAbsY`](#LuaItemNull_GetAbsY)
[`SetW`](#LuaItemNull_SetW)
[`SetH`](#LuaItemNull_SetH)
[`GetW`](#LuaItemNull_GetW)
[`GetH`](#LuaItemNull_GetH)
[`SetRelPos`](#LuaItemNull_SetRelPos)
[`GetRelPos`](#LuaItemNull_GetRelPos)
[`SetAbsPos`](#LuaItemNull_SetAbsPos)
[`GetAbsPos`](#LuaItemNull_GetAbsPos)
[`SetSize`](#LuaItemNull_SetSize)
[`GetSize`](#LuaItemNull_GetSize)
[`SetPosType`](#LuaItemNull_SetPosType)
[`GetPosType`](#LuaItemNull_GetPosType)
[`IsVisible`](#LuaItemNull_IsVisible)
[`GetName`](#LuaItemNull_GetName)
[`SetName`](#LuaItemNull_SetName)
[`SetTip`](#LuaItemNull_SetTip)
[`GetTip`](#LuaItemNull_GetTip)
[`SetUserData`](#LuaItemNull_SetUserData)
[`GetUserData`](#LuaItemNull_GetUserData)
[`RegisterEvent`](#LuaItemNull_RegisterEvent)
[`ClearEvent`](#LuaItemNull_ClearEvent)
[`EnableScale`](#LuaItemNull_EnableScale)
[`Scale`](#LuaItemNull_Scale)
[`LockShowAndHide`](#LuaItemNull_LockShowAndHide)
[`SetAlpha`](#LuaItemNull_SetAlpha)
[`GetAlpha`](#LuaItemNull_GetAlpha)
[`GetParent`](#LuaItemNull_GetParent)
[`GetRoot`](#LuaItemNull_GetRoot)
[`GetType`](#LuaItemNull_GetType)
[`GetIndex`](#LuaItemNull_GetIndex)
[`SetIndex`](#LuaItemNull_SetIndex)
[`ExchangeIndex`](#LuaItemNull_ExchangeIndex)
[`GetTreePath`](#LuaItemNull_GetTreePath)
[`SetAreaTestFile`](#LuaItemNull_SetAreaTestFile)
[`SetIntPos`](#LuaItemNull_SetIntPos)
[`IsIntPos`](#LuaItemNull_IsIntPos)
[`IsLink`](#LuaItemNull_IsLink)
[`GetLinkInfo`](#LuaItemNull_GetLinkInfo)
[`SetLinkInfo`](#LuaItemNull_SetLinkInfo)
[`GetAniParamID`](#LuaItemNull_GetAniParamID)
[`IsValid`](#LuaItemNull_IsValid)
[`__eq`](#LuaItemNull_Equal)
[`GetBaseType`](#LuaItemNull_GetBaseType)


* <h4 id="LuaItemNull_SetVisible">SetVisible</h4>
Set Item Visibility.
> (`void`) ItemNull:SetVisible(`bool` bVisible)

* <h4 id="LuaItemNull_Show">Show</h4>
Show Item, same as [`:SetVisible(true)`](#LuaItemNull_SetVisible).
> (`void`) ItemNull:Show()

* <h4 id="LuaItemNull_Hide">Hide</h4>
Hide Item, same as [`:SetVisible(false)`](#LuaItemNull_SetVisible).
> (`void`) ItemNull:Hide()

* <h4 id="LuaItemNull_PtInItem">PtInItem</h4>
Judge if a given screen position is in this Item. Always use with `Cursor.GetPos()`.
 > * (`bool` bIsInItem) ItemNull:PtInItem(`number` nX, `number` nY)
 > * (`bool` bIsInItem) ItemNull:PtInItem(Cursor.GetPos())

* <h4 id="LuaItemNull_SetRelX">SetRelX</h4>
Set Item's relative X (to its parent).
> (`void`) ItemNull:SetRelX(`number` nX)

* <h4 id="LuaItemNull_SetRelY">SetRelY</h4>
Set Item's relative Y (to its parent).
> (`void`) ItemNull:SetRelX(`number` nY)

* <h4 id="LuaItemNull_GetRelX">GetRelX</h4>
Get Item's relative X (to its parent).
> (`number` nX) ItemNull:GetRelX()

* <h4 id="LuaItemNull_GetRelY">GetRelY</h4>
Get Item's relative Y (to its parent).
> (`number` nY) ItemNull:GetRelY()

* <h4 id="LuaItemNull_SetAbsX">SetAbsX</h4>
Set Item's absolute X (to the screen).
> (`void`) ItemNull:SetAbsX(`number` nX)

* <h4 id="LuaItemNull_SetAbsY">SetAbsY</h4>
Set Item's absolute Y (to the screen).
> (`void`) ItemNull:SetAbsY(`number` nY)

* <h4 id="LuaItemNull_GetAbsX">GetAbsX</h4>
Get Item's absolute X (to the screen).
> (`number` nX) ItemNull:GetAbsX()

* <h4 id="LuaItemNull_GetAbsY">GetAbsY</h4>
Get Item's absolute Y (to the screen).
> (`number` nY) ItemNull:GetAbsY()

* <h4 id="LuaItemNull_SetW">SetW</h4>
Set Item's width.
> (`void`) ItemNull:SetW(`number` nW)

* <h4 id="LuaItemNull_SetH">SetH</h4>
Set Item's height.
> (`void`) ItemNull:SetH(`number` nW)

* <h4 id="LuaItemNull_GetW">GetW</h4>
Get Item's width.
> (`number` nW) ItemNull:GetW()

* <h4 id="LuaItemNull_GetH">GetH</h4>
Get Item's height.
> (`number` nH) ItemNull:GetH()

* <h4 id="LuaItemNull_SetRelPos">SetRelPos</h4>
Set Item's relative position. The union of [`:SetRelX`](#LuaItemNull_SetRelX) and [`:SetRelY`](#LuaItemNull_SetRelY).
> (`void`) ItemNull:SetRelPos(`number` nX, `number` nY)

* <h4 id="LuaItemNull_GetRelPos">GetRelPos</h4>
Get Item's relative position. The union of [`:GetRelX`](#LuaItemNull_GetRelX) and [`:GetRelY`](#LuaItemNull_GetRelY).
> (`number` nX, `number` nY) ItemNull:GetRelPos()

* <h4 id="LuaItemNull_SetAbsPos">SetAbsPos</h4>
Set Item's relative position. The union of [`:SetAbsX`](#LuaItemNull_SetAbsX) and [`:SetAbsY`](#LuaItemNull_SetAbsY).
> (`void`) ItemNull:SetAbsPos(`number` nX, `number` nY)

* <h4 id="LuaItemNull_GetAbsPos">GetAbsPos</h4>
Get Item's relative position. The union of [`:GetAbsX`](#LuaItemNull_GetAbsX) and [`:GetAbsY`](#LuaItemNull_GetAbsY).
> (`number` nX, `number` nY) ItemNull:GetAbsPos()

* <h4 id="LuaItemNull_SetSize">SetSize</h4>
Set Item's size. The union of [`:SetW`](#LuaItemNull_SetW) and [`:SetH`](#LuaItemNull_SetH).
> (`void`) ItemNull:SetSize(`number` nW, `number` nH)

* <h4 id="LuaItemNull_GetSize">GetSize</h4>
Get Item's size. The union of [`:GetW`](#LuaItemNull_GetW) and [`:GetH`](#LuaItemNull_GetH).
> (`number` nW, `number` nH) ItemNull:GetSize()

* <h4 id="LuaItemNull_SetPosType">SetPosType</h4>
Set Item's position type. See the enum of [`ITEM_POSITION`](#ITEM_POSITION).
> (`number` nW, `number` nH) ItemNull:SetPosType()

* <h4 id="LuaItemNull_GetPosType">GetPosType</h4>
Get Item's position type. See the enum of [`ITEM_POSITION`](#ITEM_POSITION).
> (`enum` nPosType) ItemNull:GetPosType()

* <h4 id="LuaItemNull_IsVisible">IsVisible</h4>
Get Item's visibility.
> (`bool` bVisible) ItemNull:IsVisible()

* <h4 id="LuaItemNull_GetName">GetName</h4>
Get Item's name.
> (`string` szName) ItemNull:GetName()

* <h4 id="LuaItemNull_SetName">SetName</h4>
Set Item's name.
> (`void`) ItemNull:SetName(`string` szName)

* <h4 id="LuaItemNull_SetTip">SetTip</h4>
Set Item's tip. When mouse enter it, the tip will be showen.
> (`void`) ItemNull:SetTip(`string` szTip)

* <h4 id="LuaItemNull_GetTip">GetTip</h4>
Get Item's tip.
> (`string` szTip) ItemNull:GetTip()

* <h4 id="LuaItemNull_SetUserData">SetUserData</h4>
Set a number to the Item.
> (`void`) ItemNull:SetUserData(`number` nData)

* <h4 id="LuaItemNull_GetUserData">GetUserData</h4>
Get Item's userdata.
> (`number` nData) ItemNull:GetUserData()

* <h4 id="LuaItemNull_RegisterEvent">RegisterEvent</h4>
Register an ui event so that this item is able to response the specified ui event such as mouse click event.
> (`void`) ItemNull:RegisterEvent(`number` nUIEvent)

* <h4 id="LuaItemNull_ClearEvent">ClearEvent</h4>
Clear all ui event on this Item.
> (`void`) ItemNull:ClearEvent()

* <h4 id="LuaItemNull_EnableScale">EnableScale</h4>
Set if this Item can be scaled.
> (`void`) ItemNull:EnableScale(`bool` bEnableScale)

* <h4 id="LuaItemNull_Scale">Scale</h4>
Scale an Item. Please noticed that it's children will also be scaled. And remember to save the scale to some place because there is no api to get current scale level. The working principle of this api is just traverse all its children and itself and make their width and height multiplied with the given scale value.
> (`void`) ItemNull:Scale(`number` fScaleX, `number` fScaleY)

* <h4 id="LuaItemNull_LockShowAndHide">LockShowAndHide</h4>
Set if this Item's default visibility is invisible.
> (`void`) ItemNull:LockShowAndHide(`bool` bEnable)

* <h4 id="LuaItemNull_SetAlpha">SetAlpha</h4>
Set its alpha. The value can be set between 0 and 255.
> (`void`) ItemNull:SetAlpha(`number` nAlpha)

* <h4 id="LuaItemNull_GetAlpha">GetAlpha</h4>
Get its alpha value (0 - 255).
> (`number` nAlpha) ItemNull:GetAlpha()

* <h4 id="LuaItemNull_GetParent">GetParent</h4>
Get its parent node. It will return `null` if it has no parent.
> (`KGUI OBJECT` pParent) ItemNull:GetParent()

* <h4 id="LuaItemNull_GetRoot">GetRoot</h4>
Get its root parent node (the frame).
> (`KGUI Frame` pFrame) ItemNull:GetRoot()

* <h4 id="LuaItemNull_GetType">GetType</h4>
Get its ui type, such as `WndWindow`, `Handle`, `Text`, etc.
> (`string` szType) ItemNull:GetType()

* <h4 id="LuaItemNull_GetIndex">GetIndex</h4>
Get its index. The value will between 0 and the count of its brothers.
> (`number` nIndex) ItemNull:GetIndex()

* <h4 id="LuaItemNull_SetIndex">SetIndex</h4>
Set its index. The value must between 0 and the count of its brothers.
> (`void`) ItemNull:SetIndex(`number` nIndex)

* <h4 id="LuaItemNull_ExchangeIndex">ExchangeIndex</h4>
Exchange the index with one of its brothers.
> * (`void`) ItemNull:ExchangeIndex(`number` nIndex)
> * (`void`) ItemNull:ExchangeIndex(`KGUI Object` pBrotherItem)

* <h4 id="LuaItemNull_GetTreePath">GetTreePath</h4>
Get the tree path of this Item.
> (`string` szWndTreePath, `string` szHandleTreePath) ItemNull:GetTreePath()

<!-- * <h4 id="LuaItemNull_SetAreaTestFile">SetAreaTestFile</h4> -->

<!-- * <h4 id="LuaItemNull_SetIntPos">SetIntPos</h4> -->

<!-- * <h4 id="LuaItemNull_IsIntPos">IsIntPos</h4> -->

<!-- * <h4 id="LuaItemNull_IsLink">IsLink</h4> -->

<!-- * <h4 id="LuaItemNull_GetLinkInfo">GetLinkInfo</h4> -->

<!-- * <h4 id="LuaItemNull_SetLinkInfo">SetLinkInfo</h4> -->

<!-- * <h4 id="LuaItemNull_GetAniParamID">GetAniParamID</h4> -->

* <h4 id="LuaItemNull_IsValid">IsValid</h4>
Check if this Item is still vaild. Once the Item get destroyed, this api will return `false`.
> (`bool` bValid) ItemNull:IsValid()

<!-- * <h4 id="LuaItemNull_Equal">__eq</h4> -->

* <h4 id="LuaItemNull_GetBaseType">GetBaseType</h4>
Get its base type. The value can be `Item` or `Wnd`.
> (`string`) ItemNull:GetBaseType()
