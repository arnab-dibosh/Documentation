![ClassVsFunctionComponent](ClassVsFunctionComponent.GIF)

![ComponentLifecycle](ComponentLifecycle.GIF)

**Constructor**: Variable and state initailization can be done. But dont call api, state or props change, api call. Avoid all kind of side effect.

**render**: No api call, settimeout. In short no blocking code.

**componentDidMount**: Dont call setState sequencially. Can do on then block

## Sequence of Execution

#### Component create
![LifeCycleSequence](LifeCycleSequence.GIF)

#### Component update
In component Update we should not call setstate synchronously, as that will cause a loop. We can call setstate in the then block of a async call
![UpdateSequence](UpdateSequence.GIF)

#### Convert person Function to Class
![PersonFuncToClass](PersonFuncToClass.GIF)

#### Convert persons Function to Class
![NowConvertPersons](NowConvertPersons.GIF)

#### useEffect
Use effect is called on every render
![UseEffect](UseEffect.GIF)

Call useEffect on persons prop change only

Use effect is called on every render
![PersonsChangeOnly](PersonsChangeOnly.GIF)

Use effect is called on every render
![ReactDomUpdate](ReactDomUpdate.GIF)

## Aux
Aux is used to wrap multiple jsx child

![Auxilary](Auxilary.GIF)

Wrapping with Aux

![WrapWithAux](WrapWithAux.GIF)

Higher Order Component

![HigherOrderComponent](HigherOrderComponent.GIF)

Wrap with Higher Order Component

![WrapWithHOC](WrapWithHOC.GIF)

Higher Order Component Called through export

![HocCalledFromExport](HocCalledFromExport.GIF)

Using hoc

![HowToUse](HowToUse.GIF)

### Forwarding props to HOC

![ForWardingPropsToHoc](ForWardingPropsToHoc.GIF)

#### Call it from Person Comp

![WithClassInPerson](WithClassInPerson.GIF)

## Setting State Correctly

Adding Change counter state at app.js

![AddingNewState](AddingNewState.GIF)

Setting Counter Value

![SetCounterValue](SetCounterValue.GIF)

Setting multiple state can cause error. React doesnt set state immediatly. So the safe way is given below:

![SettingStateCorrectly](SettingStateCorrectly.GIF)

Check State Value
![CheckStateValue](CheckStateValue.GIF)

## Define datatype in props

#### Install package

![PackageProptypes](PackageProptypes.GIF)

#### Import package

![Import](Import.GIF)

#### Define Types

![DefineTypes](DefineTypes.GIF)

Throws error if string is passed in Prop: Age instead of int 
![Error](Error.GIF)



