<template>  
  <article class="shows">
    <header>
      <h2>Shows</h2>
    </header>

<section class="past">
      <table>
        <tr>  
          <th>Date</th>
          <th>Venue</th>
          <th>Location</th>
        </tr>
        <h3>Upcoming:</h3>
        <tr>
          <td>12/29/16</td>
          <td>The Refuge</td>
          <td>Chicago, IL</td>
        </tr>
        <h3>Past:</h3>
        <tr>
          <td>9/17/16</td>
          <td>The Friendship House</td>
          <td>Chicago, IL</td>
        </tr>
        <tr>
          <td>7/1/16</td>
          <td>Moe's Tavern</td>
          <td>Chicago, IL</td>
        </tr>
        <tr>
          <td>5/27/16</td>
          <td>Tonic Room</td>
          <td>Chicago, IL</td>
        </tr>
        <tr>
          <td>3/5/16</td>
          <td>The Dollhouse DIY</td>
          <td>Chicago, IL</td>
        </tr>
        <tr>
          <td>10/10/15</td>
          <td>North Bar</td>
          <td>Chicago, IL</td>
        </tr>
        <tr>
          <td>8/22/15</td>
          <td>Hostel Earphoria</td>
          <td>Chicago, IL</td>
        </tr>
      </table>
    </section>
  </article>
</template>

<style lang="scss" scoped>

  header {
    text-align: center;
  }
  
  table {
    width: 100%;
  }

  th {
    text-align: left;
  }

  p {
    color: lighten(white, 40%);
    font-size: 1.2rem;
  }
</style>
