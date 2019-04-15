<template>
  <section class="section">
    <div class="columns is-mobile">
      <card
        title="My First Blog entry"
        icon="github-circle"
      >
        <template>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean porttitor nisl sed cursus tempus. Curabitur tortor dui, condimentum in enim blandit, iaculis porttitor orci. Praesent rutrum porta sagittis. Etiam consequat ornare mauris. Nunc vel cursus nunc. Donec quis tellus magna. Quisque eu hendrerit orci. Vivamus ullamcorper sodales enim, a facilisis dolor porta id. Aliquam eu magna nec dolor congue rutrum vitae sed lorem. Curabitur sit amet eros vitae elit mollis pretium vel non mauris. Morbi sed posuere mauris. Aliquam pretium nisl diam. Proin vestibulum sollicitudin posuere. Curabitur cursus egestas finibus. Proin luctus faucibus nunc, at euismod felis iaculis quis. Curabitur tristique magna odio, vel placerat justo commodo sit amet.
        </template>
        <template slot="footer">
          Created for the firetalk of 15/04/2019
        </template>
      </card>
    </div>
  </section>
</template>

<script>
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Card
  }
}
</script>
