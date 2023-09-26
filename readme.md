# json-beautifier

Beautify or minimize JSON.

<table>
<tr>
<th> Action </th>
<th> From </th>
<th> To </th>
</tr>
<tr>
<td>Beautify</td>
<td>

```json
  {
    "one":"two","second":[
"uno", "dos"    
]
     }
```

</td>
<td>

```json
{
    "one": "two",
    "second": [
        "uno",
        "dos"
    ]
}
```

</td>
</tr>
<tr>
<td>Minify</td>
<td>

```json
{
    "one": "two",
    "second": [
        "uno",
        "dos"
    ]
}
```

</td>
<td>

```json
{"one":"two","second":["uno","dos"]}
```

</td>
</tr>
</table>

###### from manuals of youtu.be/s38oGpnnQo8