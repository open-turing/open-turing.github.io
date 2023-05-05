---
layout: default
title: Event
---

<table>
  <thead><tr>
  <th>일시</th><th>주제</th><th>강연자</th><th>장소</th>
  </tr></thead>
  <tbody>
  {% for item in site.data.event %}
    <tr>
      <td>{{ item.date }}</td>
      <td>{{ item.title }}</td>
      <td>{{ item.speaker }}</td>
      <td>{{ item.place }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>
