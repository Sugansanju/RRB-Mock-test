<template>
<!-- <div>
<div id="wrapper">
            <div id="minwidth">
                		<div id="header">
			 <table width="100%" cellspacing="0" cellpadding="0" border="0">
				<tbody>
				  <tr>
					<td align="left" id="bannerImage">
						<div id="bannerImg" style="float:left"></div>
						<div id="bannerText" align="center" style="margin-top:10px; font-weight:bold;"><font size="4" color="#ffffff"></font></div>
					</td>
				  </tr>
				</tbody>
			  </table>
		</div>
    <div class="userInfo">
			<div class="system_info">
				<div class="system_name">
					<div id="sysName" class="name1">System Name :</div>
					<div class="details1">C001</div>
					<div style="font-size:15px;" class="details3">
						<a onclick="notMySystem();" style="color: white; text-decoration: none; border: 0 none;" id="notMySystem">Contact invigilator if the Name and Photograph<br>displayed on the screen is not yours</a>
					</div>
				</div>
				<div align="center" class="user_pic"><img width="94" height="101" align="absmiddle" class="candidateImg" src="images/NewCandidateImage.jpg"></div>
				<div class="user_name">
					<div id="indexCandName" class="name2">Candidate Name :</div>
					<div class="details2">
						<span title="John Smith " class="candOriginalName">John Smith </span>
					</div>
					<div style="margin-top:10px;text-align:right"><span class="name2" id="subName">Subject :</span><span style="font-size:15px;" class="details2">Mock Exam</span></div>
				</div>
				<div class="clear"></div>
			</div>
		</div>
                <div id="login">
                    <div class="form-header" id="LoginPageHeader">Login</div>
                    <form name="form-login">

                        <span class="fontawesome-user"></span>

                        <input type="text" name="text15" class="mandat_input keyboardInput loginText" disabled="disabled" value="11111" vki_attached="true"><img src="" alt="Display virtual keyboard interface" class="keyboardInputInitiator" title="Select keyboard layout">

                        <span class="clear"></span>

                        <span class="fontawesome-lock"></span>
                        <input type="password" value="Guest" class="mandat_input keyboardInput loginText" disabled="disabled" name="text14" vki_attached="true"><img src="" alt="Display virtual keyboard interface" class="keyboardInputInitiator" title="Select keyboard layout">
<table>
                       <tbody><tr class="multilingualDropdown" id="multilingualDropdown" style="display:none">
				<td align="right"><span class="text1" id="changeLang">Change Language </span></td>
				<td>
					<select id="languageSelect" onchange="selIndexLang(this.value);"><option value="English">English</option></select>
				</td>
			</tr></tbody></table>
                       <a onclick="openerNew()"> <span id="signInLabel" class="btn btn-primary btn-primary-blue" style="line-height: 35px">Sign In</span></a><a>

                </a></form></div><a>

            </a></div><a>
			    <div id="footer">
			    <center>
	<div> Version 17.03.00</div></center>
    <div class="clear"></div>
</div>

        </a></div>
</div> -->
<div>
<b-navbar class="nav"  type="dark"></b-navbar>
<b-row>
    <b-col cols="12" class="userInfo">
			<div class="system_info">
				<div  class="system_name">
					<div  class="name1">System Name :</div>
					<div class="details1">C001</div>
					<div style="font-size:15px;" class="details3">
						<a style="color: white; text-decoration: none; border: 0 none;">Contact invigilator if the Name and Photograph<br>displayed on the screen is not yours</a>
					</div>
				</div>
				<div align="center" class="user_pic">
          <img width="94" height="101" align="absmiddle" class="candidateImg" src="/static/images/8.png">
        </div>
				<div  class="user_name">
					<div class="name2">Candidate Name :</div>
					<div class="details2">
						<span>Harish </span>
					</div>
					<div style="margin-top:10px;text-align:right">
            <span class="name2">Subject :</span>
            <span style="font-size:15px;" class="details2">Mock Exam</span>
            </div>
				</div>
			</div>
		</b-col>
    </b-row>
           <b-col  cols="3" offset="4" style="margin-top:5%">
             <div class="card" style="background-color:#EDEDED;">
               <label style="text-align:left">Login</label>
             </div>
          <div class="card card-style">
            <div class="card-body text-center">
              <form>
        <input  class="form-control input"
                type="text"
                autofocus
                placeholder="Email/Mobile">
           <input  class="form-control input"
                type="password"
                placeholder="password">
    <br/>
           <div class="row">
              <div class="col-md-6"> </div>
                <div class="col-md-6 float-right">
                  <a href="#" class="btn btn-3">forgot password?</a>
                </div>
          </div>
           <div class="row">
              <div class="col-md-6"> </div>
                <div class="col-md-6 float-right">
                  <b-link class="btn btn-active">Signup</b-link>
                  <!-- <button autofocus class="btn btn-1 btn-white"  @keypress.prevent="login(user)">login</button> -->
                    <button autofocus class="btn btn-1 btn-white"  type="submit">login</button>
                     <br>
                 </div>
           </div>
              </form>
            </div>
          </div>
        </b-col>
<!-- <b-col cols="11" class="detail-container">
  <b-row align-h="between">
  <b-col cols="5" class="system">
  <span class="title">System name:</span><br>
  <span class="name">C001</span><br>
  <span class="content">contact invigilator if the Name and photgraph <br>displayed on the screen is not yours</span>
  </b-col>
  <b-col cols="5" class="candidate">
    <span class="title">Candidate name:</span><br>
     <span class="name">Harish</span><br>
  <span class="content"></span>
  </b-col>
  </b-row>
</b-col>
<b-col  class="avatar-container">
  <img src="/static/images/8.png" width="140" height="130"/>
</b-col> -->
</div>
</template>

<script>
export default {
name:'LoginPage',
components:{

},
data:function(){
  return{

  }
},
methods:{

}
}
</script>

<style>
.nav{
  height:40px;
  width:100%;
  display:flex;
  background-color: #1E70B2;
}

.userInfo {
    background: #DDD;
    height: 149px;
}

.userInfo .system_info {
    background: #666;
    height: 149px;
	border-bottom: 1px solid #444;
}
.userInfo .system_info .system_name {
    float: left;
}
.userInfo .name1 {
    color: #ffffff;
    font-size: 18px;
    margin-left: 20px;
    margin-top: 5px;
    text-align: left;
}

.userInfo .details1 {
    color: #fff200;
    font-size: 44px;
    margin-left: 20px;
    text-align: left;
}
.userInfo .details3 {
    color: #fff200;
    font-size: 34px;
    margin-left: 20px;
    text-align: left;
}

.userInfo .system_info .user_pic {
    background: #fafbfc none repeat scroll 0 0;
    border-bottom: 1px solid #444;
    float: right;
    height: 100%;
    vertical-align: middle;
    width: 137px;
}

.userInfo .user_pic img {
    border: 1px solid #000;
    margin-top: 20px;
}

.userInfo .system_info .user_name {
    float: right;
    padding-right: 10px;
}

.userInfo .name2 {
    color: #ffffff;
    font-size: 18px;
    margin-left: 20px;
    margin-top: 10px;
    text-align: right;
}

.userInfo .details2 {
    color: #fff200;
    font-size: 34px;
    margin-left: 5px;
    text-align: right;
}

</style>
