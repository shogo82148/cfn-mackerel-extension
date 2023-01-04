# Mackerel::Hosts::Service

An example resource schema demonstrating some basic constructs and validation rules.

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "Type" : "Mackerel::Hosts::Service",
    "Properties" : {
        "<a href="#name" title="Name">Name</a>" : <i>String</i>,
        "<a href="#memo" title="Memo">Memo</a>" : <i>String</i>
    }
}
</pre>

### YAML

<pre>
Type: Mackerel::Hosts::Service
Properties:
    <a href="#name" title="Name">Name</a>: <i>String</i>
    <a href="#memo" title="Memo">Memo</a>: <i>String</i>
</pre>

## Properties

#### Name

the name of the service

_Required_: Yes

_Type_: String

_Update requires_: [Replacement](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-replacement)

#### Memo

memo

_Required_: No

_Type_: String

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

## Return Values

### Ref

When you pass the logical ID of this resource to the intrinsic `Ref` function, Ref returns the Name.
