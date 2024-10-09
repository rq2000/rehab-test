<template>
   <!-- Sidebar -->
  <div class="container-fluid">
  <div class="row">
    <nav id="sidebar" class="col-md-4 col-lg-2 d-md-block" style="background-color: white;">
      <div class="position-sticky">
        <ul class="nav flex-column">
          <a class="" href="#"><img src="@/assets/w5mrk.svg" class="me-0" style="margin: 15px 0;" /></a>
          
          <li class="nav-item">
            <a class="nav-link bg-primary text-light" href="#" style="font-size: 15px; text-align: left; border-radius: 18px;">
              <img src="@/assets/w5dash.svg" class="me-2" /> Dashboard</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5order.svg" alt="Orders" class="me-2" /> Orders</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5pas.svg" alt="Passengers" class="me-2" /> Passengers</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5cap.svg" alt="Captains" class="me-2" /> Captains</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5cat.svg" alt="Categories" class="me-2" /> Categories</a></li>
          <hr>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5set.svg" alt="Settlement" class="me-2" /> Settlement</a></li>
          <hr>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5con.svg" alt="Contact" class="me-2" /> Contact</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5rev.svg" alt="Reviews" class="me-2" /> Reviews</a></li>

          <hr>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle text-black" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" 
            style="text-align: left;"><img src="@/assets/w5per.svg" alt="Permissions" class="me-2" /> Permissions</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5tra.svg" alt="Translation" class="me-2" /> Translation</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5edu.svg" alt="Education Video" class="me-2" /> Education Video</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5settings.svg" alt="Settings" class="me-2" /> Settings</a></li>

          <li class="nav-item">
            <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
              <img src="@/assets/w5cont.svg" alt="Content" class="me-2" /> Content</a></li>
        </ul>
      </div>
    </nav>

    <main class="col-md-9 col-lg-10" style="background-color: #F4F7FB;">
  <header>
    <nav class="navbar" style="background-color: white; width: 102%; height: 70px; padding: 0 40px;
     display: flex; justify-content: flex-start; align-items: left;">   
        <!-- Left Section -->
      <div class="left-section d-flex align-items-center">
        <div class="icon search-icon"><img src="@/assets/w5search.svg" class="me-2" /></div>
        <div class="icon grid-icon"><img src="@/assets/w5oooo.svg" class="me-2" /></div>
      </div>

      <!-- Right Section -->
      <div class="right-section d-flex align-items-center ms-auto">
        <div class="icon dark-mode-icon"><img src="@/assets/w5moon.svg" class="me-4" /></div>

        <div class="icon notifications-icon"><img src="@/assets/w5nat.svg" class="me-4" /></div>

        <div class="icon language-icon"><img src="@/assets/w5uk.svg" class="me-2" /></div>

        <div class="dropdown">
          <button
            class="btn btn-light dropdown-toggle"
            type="button"
            id="userDropdown"
            data-bs-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
            style="background-color: transparent; border: none;" >
            <img src="@/assets/w5Mathew.svg" alt="User" class="rounded-circle" width="30" />
          </button>
        </div>
      </div>
    </nav>
  </header>

  <div class="d-flex justify-content-start" style="margin-top: 50px;"> <!-- يمكنك تعديل القيمة حسب الحاجة --></div>

<!-- الهيدر الثاني -->
<div class="p-3 bg-white -bottom header-2" style=" border-radius: 13px; width: calc(118% - 220px); margin-right: 220px; margin-top: 10px;" >
  <div class="d-flex justify-content-between align-items-center">
    <h5 class="mb-0">Chat</h5>
    <div class="d-flex align-items-center">
      <img :src="require('@/assets/w5iconhome.svg')" class="me-2" />
      <img :src="require('@/assets/l.svg')" class="me-2" />
      <button style="background-color: #e3d8f3; color: #635BFF; border: none; padding: 10px 20px; border-radius: 13px; font-size: 16px; cursor: pointer;">Chat</button>
    </div>
  </div>
</div>

<div class="d-flex justify-content-start" style="margin-top: 30px;"> <!-- يمكنك تعديل القيمة حسب الحاجة --></div>

<!-- المحتوى بالمنتصف -->
<div class="d-flex justify-content-start" style=" border-radius: 20px;">
  <div class="col-md-4 p-0">
    <div class="card m-0 h-100">
      <div class="card-body">
        <div class="d-flex align-items-center justify-content-between"> <!-- استخدام justify-content-between لتوزيع المحتويات -->
    <div class="d-flex align-items-center"> <!-- أضفنا d-flex لتمكين التنسيق الأفقي -->
        <img src="@/assets/w5meth.svg" class="me-1 ms-3" /> <!-- إضافة ms-3 لإنشاء مسافة أكبر -->
        <div class="ms-4">
          <h6 class="mb-0" style="text-align: left;">Mathew Anderson</h6>
            <p class="text-muted small mb-0" style="color: #98A4AE; font-size: 13px; text-align: left;">Marketing Director</p>
        </div>
    </div>
    <button class="btn btn-link ms-auto" style="color: black; border: none;"> <!-- هذا الزر الآن محاذي لليمين -->
        <i class="bi bi-three-dots-vertical"></i> <!-- ثلاث نقاط فوق بعضها -->
    </button>
</div>

<div class="mt-4 position-relative">
    <input type="text" class="form-control ps-5" placeholder="Search contacts" style="height: 35px;" />
    <img src="@/assets/w5Search contacts.svg" alt="Search Icon" class="search-icon" style="position: absolute; 
    left: 10px; top: 50%; transform: translateY(-50%); width: 20px; height: 20px;" />
</div>

        <br />
        <div class="dropdown d-flex align-items-center"> <!-- إضافة d-flex و align-items-center لجعل العناصر في خط واحد -->
  <button class="btn text-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" 
    aria-expanded="false" style="text-align: left; font-size: 14px; color: #98A4AE; margin-right: 10px;">  
    Recent Chats 
  </button>
</div>

       <ul class="list-group">
        <li class="list-group-item d-flex align-items-center" style="border: none; background-color: #F6F7F9;">
    <img src="@/assets/w5Michell.svg" class="me-1" />
    <div class="ms-3 text-start w-100"> <!-- إضافة w-100 لجعل المحتوى يأخذ كامل العرض -->
      <div class="d-flex justify-content-between align-items-center"> <!-- استخدام justify-content-between لتوزيع الاسم والوقت -->
        <h6 class="mb-0">Michell Flintoff</h6>
        <small class="text-muted ms-auto">15 minutes</small> <!-- جعل الوقت محاذي لليمين -->
      </div>
      <p class="text-muted small mb-0" style="color: #98A4AE; font-size: 14px; font-family: Manrope;">You: Yesterday was great...</p>
    </div>
  </li>

  <li class="list-group-item d-flex align-items-center" style="border: none;">
  <img src="@/assets/w5Bianca.svg" class="me-1" />
  <div class="ms-3 text-start w-100"> <!-- إضافة w-100 لجعل المحتوى يأخذ كامل العرض -->
    <div class="d-flex justify-content-between align-items-center"> <!-- توزيع الاسم والوقت -->
      <h6 class="mb-0">Bianca Anderson</h6>
      <small class="text-muted">30 minutes</small> <!-- محاذاة الوقت لليمين -->
    </div>
    <p class="text-muted small mb-0" style="color: #98A4AE; font-size: 14px; font-family: Manrope;">Nice looking dress you...</p>
  </div>
</li>

  
<li class="list-group-item d-flex align-items-center" style="border: none;">
  <img src="@/assets/w5Andrew.svg" class="me-1" />
  <div class="ms-3 text-start w-100"> <!-- إضافة w-100 لجعل المحتوى يأخذ كامل العرض -->
    <div class="d-flex justify-content-between align-items-center"> <!-- توزيع الاسم والوقت -->
      <h6 class="mb-0">Andrew Johnson</h6>
      <small class="text-muted">2 hours</small> <!-- محاذاة الوقت لليمين -->
    </div>
    <small class="text-muted" style="color: #98A4AE; font-size: 14px; font-family: Manrope;">Sent a photo</small>
  </div>
</li>


<li class="list-group-item d-flex align-items-center" style="border: none;">
  <img src="@/assets/w5Mark Strokes.svg" class="me-1" />
  <div class="ms-3 text-start w-100"> <!-- إضافة w-100 لجعل المحتوى يأخذ كامل العرض -->
    <div class="d-flex justify-content-between align-items-center"> <!-- توزيع الاسم والوقت -->
      <h6 class="mb-0">Mark Strokes</h6>
      <small class="text-muted">5 days</small> <!-- محاذاة الوقت لليمين -->
    </div>
    <p class="text-muted small mb-0" style="color: #98A4AE; font-size: 14px; font-family: Manrope;">Lorem ipsum text sud...</p>
  </div>
</li>


<li class="list-group-item d-flex align-items-center" style="border: none;">
  <img src="@/assets/w5Marks.svg" class="me-1" />
  <div class="ms-3 text-start w-100"> <!-- إضافة w-100 لجعل المحتوى يأخذ كامل العرض -->
    <div class="d-flex justify-content-between align-items-center"> <!-- توزيع الاسم والوقت -->
      <h6 class="mb-0">Mark, Stoinus & Rish...</h6>
      <small class="text-muted">5 days</small> <!-- محاذاة الوقت لليمين -->
    </div>
    <p class="text-muted small mb-0" style="color: #98A4AE; font-size: 14px; font-family: Manrope;">Lorem ipsum text ...</p>
  </div>
</li>


<li class="list-group-item d-flex align-items-center" style="border: none;">
  <img src="@/assets/w5Bianca.svg" class="me-1" />
  <div class="ms-3 text-start w-100"> <!-- إضافة w-100 لجعل المحتوى يأخذ كامل العرض -->
    <div class="d-flex justify-content-between align-items-center"> <!-- توزيع الاسم والوقت -->
      <h6 class="mb-0">Bianca Anderson</h6>
      <small class="text-muted">30 minutes</small> <!-- محاذاة الوقت لليمين -->
    </div>
    <p class="text-muted small mb-0" style="color: #98A4AE; font-size: 14px; font-family: Manrope;">Nice looking dress you...</p>
  </div>
</li>

</ul>
      </div>
    </div>
  </div>

  <!-- البطاقة الأكبر -->
  <div class="col-md-5 p-0"> <!-- تعديل العرض هنا -->
  <div class="card m-0 h-100">
    <div class="card-body">
      <div class="d-flex align-items-center mb-3">
        <img src="@/assets/w5Michell.svg" class="me-1" />
        <div class="ms-3">
          <small class="text-muted">Away</small>
        </div>
      </div>
      <hr>

      <div v-if="showDialog" class="dialog-overlay" @click="closeDialog">
      <div class="dialog-content" @click.stop>
        <div class="dialog-header">
          <img :src="dialogIcon"  class="dialog-icon" />
          <h3 class="dialog-title">{{ dialogTitle }}</h3>
        </div>
        <p class="dialog-message">{{ dialogMessage }}</p>
        <div class="dialog-actions">
          <button class="btn-cancel" @click="closeDialog">Cancel</button>
          <button class="btn-confirm" @click="confirmAction">Yes</button>
        </div>
      </div>
    </div>

<br>
      <div class="chat-messages mb-3 flex-grow-1" style="overflow-y: auto;">
        <div class="d-flex mb-3">
          <div class="d-flex align-items-start mb-3">
            <img src="@/assets/w5androo.svg" class="me-2" style="margin-top: -5px;" />
            <div>
              <small class="text-muted text-start" style="display: block; color: gray;font-size: 13px;">Andrew, 2 hours ago</small>
              <p class="p-2 rounded mt-1 text-end" style="background-color: #EFF4FA;">If I don't like something, I'll stay away from it.</p>
            </div>
          </div>
        </div>
        <div class="d-flex mb-3 justify-content-end">
          <div class="ms-3 text-end">
            <small class="text-muted" style="font-size: 13px;">2 hours ago</small>
            <p class="p-2 rounded" style="background-color: #ECFDFD;">If I don’t like something, I’ll stay away from it.</p>
          </div>
        </div>
        <div class="d-flex align-items-start mb-3">
          <img src="@/assets/w5androo.svg" class="me-2" style="margin-top: -5px;" />
          <div>
            <small class="text-muted text-start" style="display: block; color: gray;font-size: 13px;">Andrew, 2 hours ago</small>
            <p class="p-2 rounded mt-1 text-end" style="background-color: #EFF4FA;">I want more detailed information.</p>
          </div>
        </div>
        <div class="d-flex mb-3 justify-content-end">
          <div class="ms-3 text-end">
            <small class="text-muted" style="font-size: 13px;">2 hours ago</small>
            <p class="p-2 rounded" style="background-color: #ECFDFD;">If I don’t like something, I’ll stay away from it.</p>
            <p class="p-2 rounded" style="background-color: #ECFDFD;">They got there early, and they got really good seats.</p>
          </div>
        </div>
        <div class="d-flex mb-3">
          <img src="@/assets/w5androo.svg" class="me-1" />
          <div class="ms-3">
            <small class="text-muted text-start" style="display: block; color: gray; font-size: 13px;">Andrew, 2 hours ago</small>
            <img src="@/assets/pinksq.svg" class="me-1" />
          </div>
        </div>
      </div>
<br>
<br>
<br>

      <div class="input-group position-relative">
        <input type="text" class="form-control ps-5" placeholder="Type a message" />
        <img src="@/assets/face.svg" class="icon-1" alt="Icon 1" style="position: absolute; left: 10px; top: 50%; transform: translateY(-50%); width: 20px; height: 20px;" />
        <img src="@/assets/reh.svg" class="icon-2" alt="Icon 2" style="margin-left: 10px; width: 20px; height: 20px;" />
        <img src="@/assets/dno.svg" class="icon-3" alt="Icon 3" style="margin-left: 10px; width: 20px; height: 20px;" />
        <img src="@/assets/rwa.svg" class="icon-4" alt="Icon 4" style="margin-left: 10px; width: 20px; height: 20px;" />
      </div>
    </div>
  </div>
</div>

<div class="col-md-3 p-0">
  <div class="card m-0 h-100">
    <div class="card-body">
      <div class="container">

<div class="d-flex align-items-center ms-auto">
  <a href="#" class="icon2 ms-3" @click="openDialog('EROO')">
    <img src="@/assets/EROO.svg" class="me-1" alt="Block" />
  </a>
  <a href="#" class="icon2 ms-3" @click="openDialog('DELT')">
    <img src="@/assets/DELT.svg" class="me-1" alt="Delete" />
  </a>
  <a href="#" class="icon2 ms-3" @click="openDialog('unlock')">
    <img src="@/assets/unlock.svg" class="me-1" alt="unlock" />
  </a>
  <div class="d-flex align-items-center justify-content-end">
  <a href="#" class="icon2 ms-auto me-3">
    <img src="@/assets/CALL.svg" class="me-1" alt="CALL" />
  </a>
</div>
  <a href="#" class="icon2 ms-3">
    <img src="@/assets/VEDU.svg" class="me-1" alt="VEDU" />
  </a>
  <a href="#" class="icon2 ms-auto">
  <img src="@/assets/MORE.svg" class="me-1" alt="MORE" />
</a>
</div>

<br>
        <hr>
        <div class="media">
          <div class="section-title" style="text-align: left; margin-bottom: 10px;"> Media <span style="color: gray;">(36)</span></div>

          <div class="d-flex flex-wrap justify-content-center">
            <!-- الصف الأول من الصور -->
            <img src="@/assets/w5pink.svg" class="icon-4" alt="Icon 4" />
            <img src="@/assets/w5oraing.svg" class="icon-4" alt="Icon 4" />
            <img src="@/assets/w5phone.svg" class="icon-4" alt="Icon 4" />
          </div>
          <div class="d-flex flex-wrap justify-content-center mt-2">
            <!-- الصف الثاني من الصور -->
            <img src="@/assets/w5sound.svg" class="icon-4" alt="Icon 4" />
            <img src="@/assets/w5pink.svg" class="icon-4" alt="Icon 4" />
            <img src="@/assets/w5oraing.svg" class="icon-4" alt="Icon 4" />
          </div>
        </div>

        <!-- إضافة margin-top هنا بين Media و Files -->
        <div class="files mt-4">
          <div class="section-title" style="text-align: left; margin-bottom: 10px;"> Files <span style="color: gray;">(36)</span></div>
          <div class="file-item">
            <div class="file-info">
              <div class="file-item d-flex align-items-center mb-3" style="text-align: left;">
                <img src="@/assets/pd.svg" class="icon-1 me-2" alt="Icon 1" />
                <div class="file-info">
                  <div class="file-name" style="font-size: 15px; font-weight: bold;">service-task.pdf</div>
                  <div class="file-details" style="color: gray; font-size: 12px;">2 MB 2 Dec 2022</div>
                </div>
              </div>

              <div class="file-item d-flex align-items-center mb-3" style="text-align: left;">
                <img src="@/assets/fa.svg" class="icon-1 me-2" alt="Icon 1" />
                <div class="file-info">
                  <div class="file-name" style="font-size: 15px; font-weight: bold;">homepage-design.fig</div>
                  <div class="file-details" style="color: gray; font-size: 12px;">2 MB 2 Dec 2022</div>
                </div>
              </div>

              <div class="file-item d-flex align-items-center mb-3" style="text-align: left;">
                <img src="@/assets/us.svg" class="icon-1 me-2" alt="Icon 1" />
                <div class="file-info">
                  <div class="file-name" style="font-size: 15px; font-weight: bold;">about-us.html</div>
                  <div class="file-details" style="color: gray; font-size: 12px;">2 MB 2 Dec 2022</div>
                </div>
              </div>

              <div class="file-item d-flex align-items-center mb-3" style="text-align: left;">
                <img src="@/assets/zi.svg" class="icon-1 me-2" alt="Icon 1" />
                <div class="file-info">
                  <div class="file-name" style="font-size: 15px; font-weight: bold;">work-project.zip</div>
                  <div class="file-details" style="color: gray; font-size: 12px;">2 MB 2 Dec 2022</div>
                </div>
              </div>

              <div class="file-item d-flex align-items-center mb-3" style="text-align: left;">
                <img src="@/assets/js.svg" class="icon-1 me-2" alt="Icon 1" />
                <div class="file-info">
                  <div class="file-name" style="font-size: 15px; font-weight: bold;">custom.js</div>
                  <div class="file-details" style="color: gray; font-size: 12px;">2 MB 2 Dec 2022</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
</main>

  </div>
</div>
</template>

<script>
export default {
  data() {
    return {
      showDialog: false,
      dialogTitle: '',
      dialogMessage: '',
      dialogIcon: ''
    };
  },
  methods: {
    openDialog(type) {
  if (type === 'EROO') {
    this.dialogTitle = 'Block User';
    this.dialogMessage = 'You Are Going To Block This User. Are You Sure?';
    this.dialogIcon = require('@/assets/EROO.svg'); // استخدم require لمسار الـ block
  } else if (type === 'DELT') {
    this.dialogTitle = 'Delete User';
    this.dialogMessage = 'Once You Sure To Delete This Conversation , You Will Not Be Able To Undo This Action';
    this.dialogIcon = require('@/assets/DELT.svg'); // استخدم require لمسار الـ delete
  } else if (type === 'unlock') {
    this.dialogTitle = 'Unlock User';
    this.dialogMessage = 'You Are Going To Unblock This User , Are You Sure?';
    this.dialogIcon = require('@/assets/unlock.svg'); // استخدم require لمسار الـ clip
  }
  this.showDialog = true;
},

    closeDialog() {
      this.showDialog = false;
    },
    confirmAction() {
      // تنفيذ الإجراء عند النقر على Yes
      this.closeDialog();
}
}
};

</script>

<style scoped>
body {
  background-color: white; /* Background for the entire body */
}

.navbar {
  padding: 1rem;
}

.navbar-brand {
  font-size: 1.5rem;
}

.sidebar {
  list-style-type: none;
  padding: 0;
}

.sidebar .nav-item {
  margin-bottom: 10px;
}

.dropdown-menu {
  right: 0;
  left: auto;
}

.left-section,
.right-section {
  display: flex;
  align-items:start;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.row {
  background-color: white; /* White background for the content row */
}


chat-layout {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  height: 100vh;
}

.sidebar {
  padding: 20px;
  border-right: 1px solid #ddd;
}

.search-input {

 
  width: 100%;
}
.input-group {
      position: relative;
      display: flex;
      align-items: center;
    }

    .input-group input {
      width: 100%;
      padding-right: 130px; /* مساحة إضافية للأيقونات داخل input */
      padding-left: 15px;
      height: 40px;
      font-size: 16px;
      border-radius: 5px;
      right: 10px;
    }

    /* وضع الأيقونات في الحقل */
    .input-group img {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      right: 10px; /* الأيقونة الأولى تكون عند اليمين */
      height: 24px;
      cursor: pointer;
    }

    /* ترتيب الأيقونات (الأولى، الثانية، الثالثة) */
    .input-group img:nth-child(2) {
      left: 1px;
    }

    .input-group img:nth-child(3) {
      right: 40px;
    }

    .input-group img:nth-child(4) {
      right: 70px;
    }

    .media .icon-4 {
  width: 30%; /* نسبة العرض، يمكن تعديلها لتناسب التصميم */
  margin: 3px; /* فراغ بين الصور */
  display: inline-block; /* تأكد من أن العناصر تتراص بشكل صحيح */
  vertical-align: top; /* لضبط محاذاة العناصر إذا كانت في صفوف */
  box-sizing: border-box; /* للتأكد من أن الحواف والمسافات تضاف إلى الحجم الكلي */
}

.dialog-overlay {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1000;
}

/* Dialog content */
.dialog-content {
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  width: 320px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

/* Dialog header */
.dialog-header {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 20px;
}

/* Dialog icon */
.dialog-icon {
  width: 40px;
  height: 40px;
  margin-bottom: 10px;
}

/* Dialog title */
.dialog-title {
  font-size: 18px;
  font-weight: 600;
  margin: 0;
  color: #333;
}

/* Dialog message */
.dialog-message {
  font-size: 14px;
  color: #666;
  margin-bottom: 20px;
}

/* Dialog actions (buttons) */
.dialog-actions {
  display: flex;
  justify-content: space-between;
}

/* Cancel button */
.btn-cancel {
  background-color: #ccc;
  color: #333;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 14px;
}

/* Confirm button */
.btn-confirm {
  background-color: #635bff;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 14px;
}

.btn-cancel:hover, .btn-confirm:hover {
 opacity:0.9;
}

</style>