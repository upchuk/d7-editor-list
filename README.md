## Installation

Just enable the module like you normally would, though keep in mind that it depends on the Entity Reference module.

Once enabled, you'll notice that a new field called Editors (`field_editors`) has been created on the Article content type. You should see it under the `Authoring information` group. With that field you can reference user entities that should have access to a given node. 

Keep in mind that the users you reference should not already have permission to edit all Article nodes. Otherwise this is kind of pointless.