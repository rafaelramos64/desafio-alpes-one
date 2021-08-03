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

    <div>
      <Footer />
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import Header from '@/components/Header'
import Contact from '@/components/Contact'
import DriverEmotion from '@/components/DriverEmotion'
import CivicInterior from '@/components/CivicInterior'
import Footer from '@/components/Footer'

export default {
  components: {
    Navbar,
    Header,
    Contact,
    DriverEmotion,
    CivicInterior,
    Footer
  },
  name: 'Home'
}
</script>
