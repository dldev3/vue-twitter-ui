<template>
  <div>
    <Notification />
    <Navbar />
    <PrimaryUser />
    <TweetBody/>
    <UserActions />
    <Comments/>
    <Reply />
  </div>
</template>

<script>
import Notification from './components/android/Notification';
import Navbar from './components/Navbar';
import PrimaryUser from './components/PrimaryUser';
import TweetBody from './components/TweetBody';
import UserActions from './components/UserActions';
import Comments from './components/Comments';
import Reply from './components/Reply';

export default {
  name: 'App',
  components: {
    Notification,
    Navbar,
    PrimaryUser,
    TweetBody,
    UserActions,
    Comments,
    Reply

  }
}
</script>

<style lang="scss">

</style>
