<template>
  <div>
    <div class="stories">
      <div class="story">
        <div class="profile-photo">
          <img src="../assets/images/profile-1.jpg" />
        </div>
        <p class="name">Your story</p>
      </div>
      <div class="story">
        <div class="profile-photo">
          <img src="../assets/images/profile-2.jpg" />
        </div>
        <p class="name">Polonchi Pistonchi</p>
      </div>
      <div class="story">
        <div class="profile-photo">
          <img src="../assets/images/profile-3.jpg" />
        </div>
        <p class="name">Yusupov Erkinjon</p>
      </div>
      <div class="story">
        <div class="profile-photo">
          <img src="../assets/images/profile-4.jpg" />
        </div>
        <p class="name">Jhon Doe</p>
      </div>
      <div class="story">
        <div class="profile-photo">
          <img src="../assets/images/profile-5.jpg" />
        </div>
        <p class="name">Karimov Zohidjon</p>
      </div>
      <div class="story">
        <div class="profile-photo">
          <img src="../assets/images/profile-5.jpg" />
        </div>
        <p class="name">Karimov Zohidjon</p>
      </div>
    </div>
    <!-- ===========end stories======= -->
    <form class="create-post">
      <div class="profile-photo">
        <img src="../assets/images/profile-1.jpg" />
      </div>
      <input
        type="text"
        placeholder="Nimalar haqida o'ylayabsiz Diana?"
        id="create-post"
      />
      <label class="btn btn-primary" for="crate-post">Post</label>
    </form>
    <!-- =======feeds========== -->
    <div class="feeds">
      <div class="feed">
        <div class="head">
          <div class="user">
            <div class="profile-photo">
              <img src="../assets/images/profile-13.jpg" />
            </div>
            <div class="ingo">
              <h3>Lana Rose</h3>
              <small>Dubai, 15 MINUT OLDIN</small>
            </div>
          </div>
          <span class="edit">
            <i class="uil uil-ellipsis-h"></i>
          </span>
        </div>
        <!-- =====post body ====-->
        <div class="photo">
          <img src="../assets/images/feed-1.jpg" />
        </div>
        <div class="action-buttons">
          <div class="interaction-buttons">
            <span><i class="uil uil-heart"></i></span>
            <span><i class="uil uil-comment-dots"></i></span>
            <span><i class="uil uil-share-alt"></i></span>
          </div>
          <div class="bookmark">
            <span><i class="uil uil-bookmark-full"></i></span>
          </div>
        </div>
        <div class="liked-by">
          <span><img src="../assets/images/profile-10.jpg" /></span>
          <span><img src="../assets/images/profile-15.jpg" /></span>
          <span><img src="../assets/images/profile-17.jpg" /></span>
          <p>Liked by <b>Polonchi Pistonchi</b> and <b>2,3456 others</b></p>
        </div>
        <div class="caption">
          <p>
            <b>Lena Rose</b> Lorem ipsum dolor sit amet consectetur adipisicing
            elit.
            <span class="harsh-tag">#lifestyle</span>
          </p>
        </div>
        <div class="comments text-muted">View all 277 comments</div>
      </div>
    </div>
    <div class="feeds">
      <div class="feed">
        <div class="head">
          <div class="user">
            <div class="profile-photo">
              <img src="../assets/images/profile-13.jpg" />
            </div>
            <div class="ingo">
              <h3>Lana Rose</h3>
              <small>Dubai, 15 MINUT OLDIN</small>
            </div>
          </div>
          <span class="edit">
            <i class="uil uil-ellipsis-h"></i>
          </span>
        </div>
        <!-- =====post body ====-->
        <div class="photo">
          <img src="../assets/images/feed-2.jpg" />
        </div>
        <div class="action-buttons">
          <div class="interaction-buttons">
            <span><i class="uil uil-heart"></i></span>
            <span><i class="uil uil-comment-dots"></i></span>
            <span><i class="uil uil-share-alt"></i></span>
          </div>
          <div class="bookmark">
            <span><i class="uil uil-bookmark-full"></i></span>
          </div>
        </div>
        <div class="liked-by">
          <span><img src="../assets/images/profile-10.jpg" /></span>
          <span><img src="../assets/images/profile-15.jpg" /></span>
          <span><img src="../assets/images/profile-17.jpg" /></span>
          <p>Liked by <b>Polonchi Pistonchi</b> and <b>2,3456 others</b></p>
        </div>
        <div class="caption">
          <p>
            <b>Lena Rose</b> Lorem ipsum dolor sit amet consectetur adipisicing
            elit.
            <span class="harsh-tag">#lifestyle</span>
          </p>
        </div>
        <div class="comments text-muted">View all 277 comments</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "middle",
};
</script>
