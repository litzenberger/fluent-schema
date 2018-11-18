## Functions

<dl>
<dt><a href="#FluentSchema">FluentSchema([options])</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>Represents a FluentSchema.</p>
</dd>
<dt><a href="#id">id(id)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>It defines a URI for the schema, and the base URI that other URI references within the schema are resolved against.
<a href="https://json-schema.org/latest/json-schema-core.html#id-keyword">reference</a></p>
</dd>
<dt><a href="#title">title(title)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>It can be used to decorate a user interface with information about the data produced by this user interface. A title will preferably be short.
<a href="https://json-schema.org/latest/json-schema-validation.html#rfc.section.10.1">reference</a></p>
</dd>
<dt><a href="#description">description(description)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>It can be used to decorate a user interface with information about the data
produced by this user interface. A description provides explanation about
the purpose of the instance described by the schema.
<a href="https://json-schema.org/latest/json-schema-validation.html#rfc.section.10.1">reference</a></p>
</dd>
<dt><a href="#examples">examples(examples)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>The value of this keyword MUST be an array.
There are no restrictions placed on the values within the array.
<a href="https://json-schema.org/latest/json-schema-validation.html#rfc.section.10.4">reference</a></p>
</dd>
<dt><a href="#ref">ref(ref)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>The value must be a valid id e.g. #properties/foo</p>
</dd>
<dt><a href="#definition">definition(name, props)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>The &quot;definitions&quot; keywords provides a standardized location for schema authors to inline re-usable JSON Schemas into a more general schema.
There are no restrictions placed on the values within the array.
<a href="reference">https://json-schema.org/latest/json-schema-validation.html#rfc.section.9</a></p>
</dd>
<dt><a href="#prop">prop(name, props)</a> ⇒ <code><a href="#FluentSchema">FluentSchema</a></code></dt>
<dd><p>The value of &quot;properties&quot; MUST be an object. Each value of this object MUST be a valid JSON Schema
<a href="reference">https://json-schema.org/latest/json-schema-validation.html#rfc.section.6.5.4</a></p>
</dd>
</dl>

<a name="FluentSchema"></a>

## FluentSchema([options]) ⇒ [<code>FluentSchema</code>](#FluentSchema)

Represents a FluentSchema.

**Kind**: global function

| Param                 | Type                                       | Default            | Description                                        |
| --------------------- | ------------------------------------------ | ------------------ | -------------------------------------------------- |
| [options]             | <code>Object</code>                        |                    | Options                                            |
| [options.schema]      | [<code>FluentSchema</code>](#FluentSchema) |                    | Default schema                                     |
| [options.generateIds] | <code>boolean</code>                       | <code>false</code> | generate the id automatically e.g. #properties.foo |

<a name="id"></a>

## id(id) ⇒ [<code>FluentSchema</code>](#FluentSchema)

It defines a URI for the schema, and the base URI that other URI references within the schema are resolved against.
[reference](https://json-schema.org/latest/json-schema-core.html#id-keyword)

**Kind**: global function

| Param | Type                | Description |
| ----- | ------------------- | ----------- |
| id    | <code>string</code> | an #id      |

<a name="title"></a>

## title(title) ⇒ [<code>FluentSchema</code>](#FluentSchema)

It can be used to decorate a user interface with information about the data produced by this user interface. A title will preferably be short.
[reference](https://json-schema.org/latest/json-schema-validation.html#rfc.section.10.1)

**Kind**: global function

| Param | Type                |
| ----- | ------------------- |
| title | <code>string</code> |

<a name="description"></a>

## description(description) ⇒ [<code>FluentSchema</code>](#FluentSchema)

It can be used to decorate a user interface with information about the data
produced by this user interface. A description provides explanation about
the purpose of the instance described by the schema.
[reference](https://json-schema.org/latest/json-schema-validation.html#rfc.section.10.1)

**Kind**: global function

| Param       | Type                |
| ----------- | ------------------- |
| description | <code>string</code> |

<a name="examples"></a>

## examples(examples) ⇒ [<code>FluentSchema</code>](#FluentSchema)

The value of this keyword MUST be an array.
There are no restrictions placed on the values within the array.
[reference](https://json-schema.org/latest/json-schema-validation.html#rfc.section.10.4)

**Kind**: global function

| Param    | Type                |
| -------- | ------------------- |
| examples | <code>string</code> |

<a name="ref"></a>

## ref(ref) ⇒ [<code>FluentSchema</code>](#FluentSchema)

The value must be a valid id e.g. #properties/foo

**Kind**: global function

| Param | Type                |
| ----- | ------------------- |
| ref   | <code>string</code> |

<a name="definition"></a>

## definition(name, props) ⇒ [<code>FluentSchema</code>](#FluentSchema)

The "definitions" keywords provides a standardized location for schema authors to inline re-usable JSON Schemas into a more general schema.
There are no restrictions placed on the values within the array.
[https://json-schema.org/latest/json-schema-validation.html#rfc.section.9](reference)

**Kind**: global function

| Param | Type                                       |
| ----- | ------------------------------------------ |
| name  | <code>string</code>                        |
| props | [<code>FluentSchema</code>](#FluentSchema) |

<a name="prop"></a>

## prop(name, props) ⇒ [<code>FluentSchema</code>](#FluentSchema)

The value of "properties" MUST be an object. Each value of this object MUST be a valid JSON Schema
[https://json-schema.org/latest/json-schema-validation.html#rfc.section.6.5.4](reference)

**Kind**: global function

| Param | Type                                       |
| ----- | ------------------------------------------ |
| name  | <code>string</code>                        |
| props | [<code>FluentSchema</code>](#FluentSchema) |
