# [{{definition}}](https://github.com/{{repository}}/tree/master/containers/{{definition}})
{{#if annotation}}
{{{annotation}}}
{{/if}}

**Image version:** {{version}}

**Source release/branch:** [{{release}}](https://github.com/{{repository}}/tree/{{release}}/containers/{{definition}})

{{#if hasVariants}}
**Definition variations:**
{{#each variants}}
- [{{this}}](#variant-{{this}})
{{/each}}

{{/if}}