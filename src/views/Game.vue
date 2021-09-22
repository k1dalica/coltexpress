<template>
  <div>
    <train />
  </div>
</template>

<script>
export default {
  data () {
    return {
      started: false,
      round: 0,
      playerToPlay: 0,
      usedCards: [],
      roundCards: [],

      players: [
        {
          role: 'TUCO',
          inside: true,
          trainIndex: 1,
          bullts: [
            'TUCO_BULLET_6',
            'TUCO_BULLET_5',
            'TUCO_BULLET_4',
            'TUCO_BULLET_3',
            'TUCO_BULLET_2',
            'TUCO_BULLET_1'
          ],
          allCards: [],
          deck: [],
          hand: [],
          money: []
        }
      ]
    }
  }
}
</script>
