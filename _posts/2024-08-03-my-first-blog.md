---
layout: default
title: "Jiten's first blog"
permalink: "/my-first-blog"
---


<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">

    <title>My page title</title>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300%7CSonsie+One" rel="stylesheet" type="text/css">
    <link rel="stylesheet" href="style.css">
  </head>

  <body>
    <!-- Here is our main header that is used across all the pages of our website -->

    <header>
      <h1>Header</h1>
    </header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Our team</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Contact</a></li>
      </ul>

      <!-- A Search form is another common non-linear way to navigate through a website. -->

      <form>
        <input type="search" name="q" placeholder="Search query">
        <input type="submit" value="Go!">
      </form>
    </nav>

    <!-- Here is our page's main content -->
    <main>

      <!-- It contains an article -->
      <article>
        <h2>Article heading</h2>

        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt congue enim, ut porta lorem lacinia consectetur.</p>

        <h3>subsection</h3>

        <p>Donec ut librero sed accu vehicula ultricies a non tortor. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean ut gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.</p>

        <p>Pelientesque auctor nisi id magna consequat sagittis. Curabitur dapibus, enim sit amet elit pharetra tincidunt feugiat nist imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.</p>

        <h3>Another subsection</h3>

        <p>Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum soclis natoque penatibus et manis dis parturient montes, nascetur ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem facilisis semper ac in est.</p>

        <p>Vivamus fermentum semper porta. Nunc diam velit, adipscing ut tristique vitae sagittis vel odio. Maecenas convallis ullamcorper ultricied. Curabitur ornare, ligula semper consectetur sagittis, nisi diam iaculis velit, is fringille sem nunc vet mi.</p>
      </article>

      <table>
      <caption>A summary of the UK's most famous punk bands</caption>
      <thead>
        <tr>
          <th scope="col">Band</th>
          <th scope="col">Year formed</th>
          <th scope="col">No. of Albums</th>
          <th scope="col">Most famous song</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">Buzzcocks</th>
          <td>1976</td>
          <td>9</td>
          <td>Ever fallen in love (with someone you shouldn't've)</td>
        </tr>
        <tr>
          <th scope="row">The Clash</th>
          <td>1976</td>
          <td>6</td>
          <td>London Calling</td>
        </tr>
        <tr>
          <th scope="row">The Damned</th>
          <td>1976</td>
          <td>10</td>
          <td>Smash it up</td>
        </tr>
        <tr>
          <th scope="row">Sex Pistols</th>
          <td>1975</td>
          <td>1</td>
          <td>Anarchy in the UK</td>
        </tr>
        <tr>
          <th scope="row">Sham 69</th>
          <td>1976</td>
          <td>13</td>
          <td>If The Kids Are United</td>
        </tr>
        <tr>
          <th scope="row">Siouxsie and the Banshees</th>
          <td>1976</td>
          <td>11</td>
          <td>Hong Kong Garden</td>
        </tr>
        <tr>
          <th scope="row">Stiff Little Fingers</th>
          <td>1977</td>
          <td>10</td>
          <td>Suspect Device</td>
        </tr>
        <tr>
          <th scope="row">The Stranglers</th>
          <td>1974</td>
          <td>17</td>
          <td>No More Heroes</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <th scope="row" colspan="2">Total albums</th>
          <td colspan="2">77</td>
        </tr>
      </tfoot>
    </table>

      <!-- the aside content can also be nested within the main content -->
      <aside>
        <h2>Related</h2>

        <ul>
          <li><a href="#">Oh I do like to be beside the seaside</a></li>
          <li><a href="#">Oh I do like to be beside the sea</a></li>
          <li><a href="#">Although in the North of England</a></li>
          <li><a href="#">It never stops raining</a></li>
          <li><a href="#">Oh well...</a></li>
        </ul>
      </aside>

    </main>

    <!-- And here is our main footer that is used across all the pages of our website -->

    <footer>
      <p>©Copyright 2050 by jiten. All rights reversed.</p>
    </footer>

  </body>
</html>