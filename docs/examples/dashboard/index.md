---
layout: example
title: Dashboard Template
group: material-design
---

<!-- Custom styles for this template -->
<link href="dashboard.css" rel="stylesheet">


<div class="pos-f-t">
  <!--div class="collapse" id="navbar-header">
    <div class="container-fluid bg-inverse p-a-1">
      <h3>Collapsed content</h3>
      <p>Toggleable via the navbar brand.</p>
    </div>
  </div-->
  <div class="navbar navbar-light bg-faded navbar-static-top">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-header">
      <i class="material-icons">menu</i>
    </button>
    
    <ul class="nav navbar-nav pull-xs-right">
      <li class="nav-item active">
        <a class="nav-link" href="#">
          <i class="material-icons">search</i>
        </a>
        <!--form class="form-inline pull-xs-right">
          <input class="form-control" type="text" placeholder="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form-->            
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <i class="material-icons">more_vert</i>
        </a>
      </li>
    </ul>
  </div>
</div>

<div class="container">
  <div class="jumbotron">
    <h1>Navbar example</h1>
    <p class="lead">This example is a quick exercise to illustrate how fixed to top navbar works. As you scroll, it will remain fixed to the top of your browser's viewport.</p>
    <a class="btn btn-lg btn-primary" href="../../components/#navbar" role="button">View navbar docs &raquo;</a>
  </div>
</div>