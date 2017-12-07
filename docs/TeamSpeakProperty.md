<a name="TeamSpeakProperty"></a>

## TeamSpeakProperty
TeamSpeak Property Class

**Kind**: global class  

* [TeamSpeakProperty](#TeamSpeakProperty)
    * [new TeamSpeakProperty(parent)](#new_TeamSpeakProperty_new)
    * [.on(name, cb)](#TeamSpeakProperty+on) ⇒ <code>undefined</code>
    * [.removeAllListeners()](#TeamSpeakProperty+removeAllListeners) ⇒ <code>undefined</code>
    * [.execute(Command, [Object], [Array], [Boolean])](#TeamSpeakProperty+execute) ⇒ <code>Promise.&lt;object&gt;</code>
    * [.execute(Command, [Object], [Array], [Boolean])](#TeamSpeakProperty+execute) ⇒ <code>Promise.&lt;object&gt;</code>
    * [._commandCache(args)](#TeamSpeakProperty+_commandCache) ⇒ <code>Promise.&lt;object&gt;</code>
    * [.filter(array, filter)](#TeamSpeakProperty+filter) ⇒ <code>Promise.&lt;object&gt;</code>
    * [.getCache()](#TeamSpeakProperty+getCache) ⇒ <code>object</code>

<a name="new_TeamSpeakProperty_new"></a>

### new TeamSpeakProperty(parent)
Creates a new TeamSpeak Property


| Param | Type | Description |
| --- | --- | --- |
| parent | <code>object</code> | The Parent Object which is a TeamSpeak Instance |

<a name="TeamSpeakProperty+on"></a>

### teamSpeakProperty.on(name, cb) ⇒ <code>undefined</code>
Subscribes to parent Events

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Version**: 1.0  

| Param | Type | Description |
| --- | --- | --- |
| name | <code>string</code> | The Event Name which should be subscribed to |
| cb | <code>function</code> | The Callback |

<a name="TeamSpeakProperty+removeAllListeners"></a>

### teamSpeakProperty.removeAllListeners() ⇒ <code>undefined</code>
Safely unsubscribes to all Events

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Version**: 1.0  
<a name="TeamSpeakProperty+execute"></a>

### teamSpeakProperty.execute(Command, [Object], [Array], [Boolean]) ⇒ <code>Promise.&lt;object&gt;</code>
Sends a command to the TeamSpeak Server.

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Returns**: <code>Promise.&lt;object&gt;</code> - Promise object which returns the Information about the Query executed  
**Async**:   
**Version**: 1.0  

| Param | Type | Description |
| --- | --- | --- |
| Command | <code>string</code> | The Command which should get executed on the TeamSpeak Server |
| [Object] | <code>object</code> | Optional the Parameters |
| [Array] | <code>object</code> | Optional Flagwords |
| [Boolean] | <code>boolean</code> | Optional if the Command should be cached |

<a name="TeamSpeakProperty+execute"></a>

### teamSpeakProperty.execute(Command, [Object], [Array], [Boolean]) ⇒ <code>Promise.&lt;object&gt;</code>
Sends a command to the TeamSpeak Server.

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Returns**: <code>Promise.&lt;object&gt;</code> - Promise object which returns the Information about the Query executed  
**Async**:   
**Version**: 1.0  

| Param | Type | Description |
| --- | --- | --- |
| Command | <code>string</code> | The Command which should get executed on the TeamSpeak Server |
| [Object] | <code>object</code> | Optional the Parameters |
| [Array] | <code>object</code> | Optional Flagwords |
| [Boolean] | <code>boolean</code> | Optional if the Command should be cached |

<a name="TeamSpeakProperty+_commandCache"></a>

### teamSpeakProperty._commandCache(args) ⇒ <code>Promise.&lt;object&gt;</code>
Sends a command to the TeamSpeak Server.

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Returns**: <code>Promise.&lt;object&gt;</code> - Promise object which returns the Information about the Query executed  
**Async**:   
**Version**: 1.0  

| Param | Type | Description |
| --- | --- | --- |
| args | <code>object</code> | Arguments which the Query should execute |

<a name="TeamSpeakProperty+filter"></a>

### teamSpeakProperty.filter(array, filter) ⇒ <code>Promise.&lt;object&gt;</code>
Filters an Object with given Option

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Returns**: <code>Promise.&lt;object&gt;</code> - Promise object  
**Async**:   
**Version**: 1.0  

| Param | Type | Description |
| --- | --- | --- |
| array | <code>object</code> | The Object which should get filtered |
| filter | <code>object</code> | Filter Object |

<a name="TeamSpeakProperty+getCache"></a>

### teamSpeakProperty.getCache() ⇒ <code>object</code>
Returns the data from the last List Command

**Kind**: instance method of [<code>TeamSpeakProperty</code>](#TeamSpeakProperty)  
**Version**: 1.0  