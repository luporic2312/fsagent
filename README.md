fsagent Cookbook
================
This cookbook will install a firescope linux agent on any RHEL/Centos/SLES host.

e.g.
This cookbook makes your favorite breakfast sandwich.

Assumptions
-----------
This cookbook assumes the following:
1) the agent files are staged on a local vm for simplicity. For a real configuration scenario, agent should be hosted on an available URL
2) the agent comes with an installer. Ideal preference would be to add the installer via an RPM 
3) enhancements. Add additional code to allow for an msi installer on windows. add node attributes into source file

Requirements
------------
TODO: List your cookbook requirements. Be sure to include any requirements this cookbook has on platforms, libraries, other cookbooks, packages, operating systems, etc.

e.g.
#### packages

cookbook will pull down latest agent from a URL
Attributes
----------
TODO: List your cookbook attributes here.

e.g.
#### fsagent::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['fsagent']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### fsagent::default
TODO: Write usage instructions for each cookbook.

e.g.
Just include `fsagent` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[fsagent]"
  ]
}
```

Contributing
------------
TODO: (optional) If this is a public cookbook, detail the process for contributing. If this is a private cookbook, remove this section.


1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: luporic2312
