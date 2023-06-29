---
title: ConstructEmailMessageTask
description: API reference for ConstructEmailMessageTask in Umbraco Commerce
---
## ConstructEmailMessageTask

```csharp
public class ConstructEmailMessageTask : 
    PipelineTaskWithTypedArgsBase<EmailSendPipelineArgs, EmailContext>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.Email.Tasks](README.md)

### Constructors

#### ConstructEmailMessageTask

```csharp
public ConstructEmailMessageTask(ITranslationService translationService)
```


### Methods

#### Execute

```csharp
public override PipelineResult<EmailContext> Execute(EmailSendPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->