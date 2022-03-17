<template>
  <div>
    <div class="messages">
      <div class="heading">
        <h4>Messages</h4>
        <i class="uil uil-edit"></i>
      </div>
      <!-- ===========search bar======== -->
      <div class="search-bar">
        <i class="uil uil-search"></i>
        <input
          type="search"
          placeholder="Search messages"
          id="message-search"
        />
      </div>
      <!-- ============message category =================-->
      <div class="category">
        <h6 class="active">Primary</h6>
        <h6>General</h6>
        <h6 class="message-requests">Request(2)</h6>
      </div>
      <!-- ============message========== -->
      <div class="message">
        <div class="profile-photo">
          <img src="../assets/images/profile-13.jpg" />
          <div class="active"></div>
        </div>
        <div class="message-body">
          <h5>Edem Quest</h5>
          <p class="text-muted">Just woke up bruh</p>
        </div>
      </div>
      <div class="message">
        <div class="profile-photo">
          <img src="../assets/images/profile-13.jpg" />
          <div class="active"></div>
        </div>
        <div class="message-body">
          <h5>Edem Quest</h5>
          <p class="text-bold">Just woke up bruh</p>
        </div>
      </div>
      <!-- ============end of message=========== -->
    </div>
    <!--============ friend request=========== -->
    <div class="friend-requests">
      <h4>Requests</h4>
      <div class="request_">
        <div class="info_">
          <div class="profile-photo">
            <img src="../assets/images/profile-18.jpg" />
          </div>
          <div>
            <h5>Hajia Bintu</h5>
            <p class="text-muted">8 mutual friends</p>
          </div>
        </div>
        <div class="action_">
          <button class="btn btn-primary">Accept</button>
          <button class="btn">Decline</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "right",
};
</script>
