<template>
  <div>
    <div>
      <Navbar />
    </div>

    <div>
      <Header />
    </div>

    <div>
      <Contact />
    </div>

    <div>
      <DriverEmotion />
    </div>

    <div>
      <CivicInterior />
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import Header from '@/components/Header'
import Contact from '@/components/Contact'
import DriverEmotion from '@/components/DriverEmotion'
import CivicInterior from '@/components/CivicInterior'

export default {
  components: {
    Navbar,
    Header,
    Contact,
    DriverEmotion,
    CivicInterior
  },
  name: 'Home'
}
</script>
