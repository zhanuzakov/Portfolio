<template>
    <div>
        <h1 class="content-title"><font-awesome-icon icon="user-circle" class="icon"/> About</h1>
        <div>
            <div class="about">
              <div class="me">
                <h2><font-awesome-icon icon="pen" class="icon"/> Full name</h2>
                <p class="text">Ali Zhanuzak</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="school" class="icon"/> Education</h2>
                <p class="text">Astana IT University</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="school" class="icon"/> Educational program</h2>
                <p class="text">Cybersecurity</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="birthday-cake" class="icon"/> Birthday</h2>
                <p class="text">2003-01-12</p>
              </div>
            </div>
            

            
        </div>
    </div>
</template>


<style scoped>
.about{
    display:inline-flex;
    padding-left: 5%;
    padding-right: 5%;
    
}



.resent{
  margin-top: 50px;
}

.me{
    margin:0 50px;
}

.text{
  font-weight: 300;
}


@media screen and (max-width: 768px){
	.about {
		flex-direction: column;
	}

	.me {
    margin: 0 auto;
	}
}
</style>