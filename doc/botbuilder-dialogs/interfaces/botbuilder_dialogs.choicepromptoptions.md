[Bot Builder SDK - Dialogs](../README.md) > [ChoicePromptOptions](../interfaces/botbuilder_dialogs.choicepromptoptions.md)



# Interface: ChoicePromptOptions

## Hierarchy


 [PromptOptions](botbuilder_dialogs.promptoptions.md)

**↳ ChoicePromptOptions**








## Properties
<a id="choices"></a>

### «Optional» choices

**●  choices**:  *(`string`⎮[Choice]())[]* 

*Defined in [libraries/botbuilder-dialogs/lib/prompts/choicePrompt.d.ts:27](https://github.com/Microsoft/botbuilder-js/blob/dfb4aa4/libraries/botbuilder-dialogs/lib/prompts/choicePrompt.d.ts#L27)*



List of choices to recognize.




___

<a id="prompt"></a>

### «Optional» prompt

**●  prompt**:  *`string`⎮[Partial]()[Activity]()* 

*Inherited from [PromptOptions](botbuilder_dialogs.promptoptions.md).[prompt](botbuilder_dialogs.promptoptions.md#prompt)*

*Defined in [libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts:12](https://github.com/Microsoft/botbuilder-js/blob/dfb4aa4/libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts#L12)*



(Optional) Initial prompt to send the user.




___

<a id="retryprompt"></a>

### «Optional» retryPrompt

**●  retryPrompt**:  *`string`⎮[Partial]()[Activity]()* 

*Inherited from [PromptOptions](botbuilder_dialogs.promptoptions.md).[retryPrompt](botbuilder_dialogs.promptoptions.md#retryprompt)*

*Defined in [libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts:16](https://github.com/Microsoft/botbuilder-js/blob/dfb4aa4/libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts#L16)*



(Optional) Retry prompt to send the user.




___

<a id="retryspeak"></a>

### «Optional» retrySpeak

**●  retrySpeak**:  *`undefined`⎮`string`* 

*Inherited from [PromptOptions](botbuilder_dialogs.promptoptions.md).[retrySpeak](botbuilder_dialogs.promptoptions.md#retryspeak)*

*Defined in [libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts:18](https://github.com/Microsoft/botbuilder-js/blob/dfb4aa4/libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts#L18)*



(Optional) Retry SSML to send the user.




___

<a id="speak"></a>

### «Optional» speak

**●  speak**:  *`undefined`⎮`string`* 

*Inherited from [PromptOptions](botbuilder_dialogs.promptoptions.md).[speak](botbuilder_dialogs.promptoptions.md#speak)*

*Defined in [libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts:14](https://github.com/Microsoft/botbuilder-js/blob/dfb4aa4/libraries/botbuilder-dialogs/lib/prompts/prompt.d.ts#L14)*



(Optional) Initial SSML to send the user.




___

<a id="style"></a>

### «Optional» style

**●  style**:  *[ListStyle](../enums/botbuilder_dialogs.liststyle.md)* 

*Defined in [libraries/botbuilder-dialogs/lib/prompts/choicePrompt.d.ts:29](https://github.com/Microsoft/botbuilder-js/blob/dfb4aa4/libraries/botbuilder-dialogs/lib/prompts/choicePrompt.d.ts#L29)*



Preferred style of the choices sent to the user. The default value is `ChoicePromptStyle.auto`.




___

