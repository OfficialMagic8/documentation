---
description: A mix of tools for administrators and users - Requires Manage Server
---

# ⚙️ Utility Commands

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Usage</th>
      <th style="text-align:left">Information</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">*clear</td>
      <td style="text-align:left">&lt;1-100&gt;</td>
      <td style="text-align:left">
        <p><b>Aliases:</b>  <code>purge, del</code>
        </p>
        <p><b>Description:</b> Clear messages in a channel</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">listmanager</td>
      <td style="text-align:left"><a href="utilities.md#list-manager-usage">click here</a>
      </td>
      <td style="text-align:left">
        <p><b>Aliases: </b><code>lm</code>
        </p>
        <p><b>Description: </b>An entire list management system that</p>
        <p>can be used for to-do-lists or a randomizer</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">randomnumber</td>
      <td style="text-align:left">
        <p>&lt;number&gt; [number]</p>
        <p><a href="utilities.md#random-number-usage">click here</a>
        </p>
      </td>
      <td style="text-align:left">
        <p><b>Aliases:</b>  <code>rn</code>
        </p>
        <p><b>Description:</b> Generate a random whole number</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">*say</td>
      <td style="text-align:left">&lt;message&gt;</td>
      <td style="text-align:left">
        <p><b>Aliases: </b><code>none</code>
        </p>
        <p>Sends a message as Magic8</p>
      </td>
    </tr>
  </tbody>
</table>

\*Requires `Manage Messages` permission to use.

## Clear Usage

...coming soon...

## List Manager Usage

An interactive setup-menu will appear when adding/removing items. A list is provided as a way to "select" what is list is being edited. The **bolded** commands are available to everyone while the others require `Manage Server`.

| Sub-Command | Usage | Information |
| :--- | :--- | :--- |
| add | &lt;list&gt; | Add an item to the list provided |
| bulkadd | &lt;list&gt; | Add multiple items to the list provided |
| remove | &lt;list&gt; | Remove an item from  |
| create | &lt;list&gt; | Create a list |
| delete | &lt;list&gt; | Delete a list |
| cooldown | &lt;5-300 seconds&gt; | Set the randomization cooldown for all users |
| **randomize** | &lt;list&gt; \[2-total items\] | Randomize a list once or multiple times without repeats |
| **view** | \[list\] | View all lists or items of a list |

## Random Number Usage

The `randomnumber` command has two options. Providing **one** number will set the minimum to **zero**. Providing **two** numbers sets the minimum to the first number, and the maximum to the second number. Negative numbers are supported while fractions are not.

