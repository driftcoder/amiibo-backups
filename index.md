# About
These Amiibo Backups work just like the real Amiibo. They are perfect to take on the go with
you instead of your precious figures. If you are a collector, these will allow you to keep your
collectibles unopened.

# Available Amiibo

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: left">Series</th>
      <th style="text-align: left">Notes</th>
    </tr>
  </thead>
  <tbody>
    {% for amiibo in site.data.amiibo.units %}
      <tr>
        <td style="text-align: left"><strong>{{ amiibo.name }}</strong></td>
        <td style="text-align: left">{{ amiibo.name }}</td>
        <td style="text-align: left"><em>{{ amiibo.notes }}</em></td>
      </tr>
    {% endfor %}
  </tbody>
</table>

{% include amiiboTable.html %}
