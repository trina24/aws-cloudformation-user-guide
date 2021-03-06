# AWS::MediaLive::Channel H265FilterSettings<a name="aws-properties-medialive-channel-h265filtersettings"></a>

Configure filters that apply to an H265 encode in the output\. This element belongs to H265Settings\.

## Syntax<a name="aws-properties-medialive-channel-h265filtersettings-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-medialive-channel-h265filtersettings-syntax.json"></a>

```
{
  "[TemporalFilterSettings](#cfn-medialive-channel-h265filtersettings-temporalfiltersettings)" : TemporalFilterSettings
}
```

### YAML<a name="aws-properties-medialive-channel-h265filtersettings-syntax.yaml"></a>

```
  [TemporalFilterSettings](#cfn-medialive-channel-h265filtersettings-temporalfiltersettings): 
    TemporalFilterSettings
```

## Properties<a name="aws-properties-medialive-channel-h265filtersettings-properties"></a>

`TemporalFilterSettings`  <a name="cfn-medialive-channel-h265filtersettings-temporalfiltersettings"></a>
Include this element only if you want to configure this filter\.  
*Required*: No  
*Type*: [TemporalFilterSettings](aws-properties-medialive-channel-temporalfiltersettings.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)