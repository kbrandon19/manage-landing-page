.profile-card{
    width:100%;
    height:auto;
    text-align: center;
    margin-bottom:3.5rem;

    .profile-card-title{

        h1{
            color:$dark-blue;}
    }

    .profile-card-bio{
        padding:0 3rem;
        margin:4rem 0 2rem 0;
        width:auto;
        height:auto;
        display:flex;
        position: relative;
        
        .card-two,.card-three,.card-four{display: none;}

        .profile-img{
            width:25%;
        }

       
        p{ color:$dark-grayish-blue;
            font-weight: 300;
            min-width: 290px;
            max-width:400px;
            margin:auto;
            text-align: center;
            font-size:14px;
            line-height: 1.7;
            }
            
    }

    .profile-card-state{
        margin-bottom:3rem;
        .bubble{
            height:5px;
            width:5px;
            border:1px solid $bright-red;
            border-radius: 25px;
            display:inline-block;
        }

        .bubble.active{
            height:5px;
            width:5px;
            border:1px solid $bright-red;
            border-radius: 25px;
            display:inline-block;
            background-color: $bright-red;
        }
    }
}



  <div class="profile-card">
    <div class="profile-card-title">
      <h1>What they've said</h1>
    </div>
    <div class="profile-card-bio">
      <div class="card-one">
        <img class="profile-img" src="/images/avatar-anisha.png" alt="">
        <h4>Anisha Li</h4>
        <p>“Manage has supercharged our team’s workflow. The ability to maintain
          visibility on larger milestones at all times keeps everyone motivated.”</p>
      </div>
      <div class="card-two">
        <img class="profile-img" src="./images/avatar-shanai.png" alt="">
        <h4>Ali Bravo</h4>
        <p> “We have been able to cancel so many other subscriptions since using
          Manage. There is no more cross-channel confusion and everyone is much
          more focused.”</p>
      </div>
      <div class="card-three">
        <img class="profile-img" src="./images/avatar-richard.png" alt="">
        <h4>Richard Watts</h4>
        <p> “Manage allows us to provide structure and process. It keeps us organized
          and focused. I can’t stop recommending them to everyone I talk to!”</p>
      </div>
      <div class="card-four">
        <img class="profile-img" src="./images/avatar-ali.png" alt="">
        <h4>Richard Watts</h4>
        <p> “Manage allows us to provide structure and process. It keeps us organized
          and focused. I can’t stop recommending them to everyone I talk to!”</p>
      </div>

    </div>
    <div class="profile-card-state">
      <div class="card1 bubble"></div>
      <div class="card2 bubble"></div>
      <div class="card3 bubble"></div>
      <div class="card4 bubble"></div>

    </div>
    <div class="profil-card-cta">
      <a href="#" class="cta-btn">Get Started</a>
    </div>
  </div>
