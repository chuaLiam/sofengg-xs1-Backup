<template>
  <v-card>
    <v-img :src="require('@/assets/MRR/MRR_2HALLWAY2.png')">
      <MapNavbar :Image1="require('@/assets/ONE_MISSION_PARK.png')"
                 :Image2="require('@/assets/MRR/CLINIC_ROOM.png')"
                 :Image3="require('@/assets/MRR/DLSUSTORE.png')"
                 :Image4="require('@/assets/MRR/ELAB_A.png')"
                 :Image5="require('@/assets/MRR/MRR_CANTEEN.png')"
                 :Image6="require('@/assets/MRR/STUDENTHUB.png')"
                 :location1="'MRR_Hub'"
                 :location2="'MRR_Canteen'"
                 :location3="'MRR_ElabA'"
                 :location4="'MRR_dlsuStore'"
                 :location5="'MRR_clinicRoom'"
                 :location6="'oneMission'"/>
      <v-layout>
        <v-flex class="text-xs-center">
          <Arrows_left :link="'/MRR_2HALLWAY3'" />
        </v-flex>
      </v-layout>
      <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> <br /> <br /> <br />
      <v-layout xs4>
        <v-flex class="text-xs-right">
        </v-flex>
      </v-layout>
      <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /> <br /> <br /> <br />
      <br /> <br /> <br /><br /> <br /> <br /> <br /> <br /><br /> <br /> <br />
      <v-layout>
        <v-flex class="text-xs-center">
          <Arrows_back :link="'/MRR_2Hallway'" />
        </v-flex>
      </v-layout>
    </v-img>
  </v-card>
</template>

<script>
import MapNavbar from '@/components/MapNavbar.vue'
import Arrows_back from '@/components/Arrows_back.vue'
import Arrows_left from '@/components/Arrows_left.vue'

export default {
  components: { MapNavbar, Arrows_back, Arrows_left },
  data () {
    return {
    }
  }
}
</script>
