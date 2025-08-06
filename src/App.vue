<script>
import Item from './components/Item.vue'

export default {
  components: {
    Item,
  },
}
</script>

<template>
  <main class="main cont">
    <ul class="items-grid">
      <li></li>

      <li class="item">
        <h2 class="item__title">Helm</h2>
        <ul class="item__list">
          <li>+86 Armor</li>
          <li>+17% Poison Res</li>
          <li>+10 Mana</li>
          <li>+11% Cold Res</li>
          <li>+8% Physical Res</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Amulet</h2>
        <ul class="item__list">
          <li>15% incr Melee Attack Speed</li>
          <li>13% incr Cold Damage</li>
          <li>+12% Chance to Ignite on Hit</li>
          <li>+8% Void Res</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Weapon left</h2>
        <ul class="item__list">
          <li>Base Attack Rate: 1.05 - Average</li>
          <li>+48 Melee Damage</li>
          <li>+15% Chance to inlict Bleed on Hit</li>
          <li>+57% Chance to inlict Bleed on Hit (?)</li>
          <li>15% incr Bleed Duration</li>
          <li>When you hit a bleeding enemy with a melee attack, all bleed stacks on that enemy double in speed</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Body</h2>
        <ul class="item__list">
          <li>qweqwe</li>
          <li>qweqwe</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Weapon right</h2>
        <ul class="item__list">
          <li>+20% Block Chance</li>
          <li>+162 Block Effectiveness</li>
          <li>+107 Armor</li>
          <li>32 Damage Reflected to Attackers</li>
          <li>5% Reduced Damage Taken on Block</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Ring left</h2>
        <ul class="item__list">
          <li>45% incr Crit Strike Chance</li>
          <li>+1 Strength</li>
          <li>+14% Phys Res</li>
          <li>+25 Health</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Belt</h2>
        <ul class="item__list">
          <li>+3 Potion Slots</li>
          <li>+40 Armor</li>
          <li>39% incr Poison Damage</li>
          <li>45% incr Chance to Find Potions</li>
          <li>11% incr Cooldown Recovery Speed</li>
          <li>+9% Crit Strike Avoidance</li>
          <li>+23 Dodge Rating</li>
          <li>Stats on this item are doubled for 1 sec after using a Potion +1 Potion Slot per equipped Weaver's Will Item</li>
          <li>49% incr Armor (?)</li>
          <li>45% of Mana Spent Gained as Ward</li>
          <li>6% more Damage to Stunned Enemies</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Ring right</h2>
        <ul class="item__list">
          <li>4% incr Movement Speed</li>
          <li>+9 Health</li>
          <li>16% Chance to gain Haste for 1 sec on Hit</li>
          <li>10% incr Melee Attack Speed</li>
          <li>43% incr Health Regen</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Gloves</h2>
        <ul class="item__list">
          <li>+10 Armor</li>
          <li>+10 Mana</li>
          <li>4.6% of Melee Damage Leeched as Health</li>
          <li>+5 Intelligence</li>
          <li>14% more Melee Damage to High Health Enemies</li>
          <li>14% more Spell Damage to Low Health Enemies</li>
          <li>10% incr Attack and Cast Speed</li>
          <li>+4 to All Attributes</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Boots</h2>
        <ul class="item__list">
          <li>+35 Armor</li>
          <li>10% incr Movement Speed</li>
          <li>6% incr Movement Speed (?)</li>
          <li>+1 Strength</li>
          <li>+13% Phys Res</li>
          <li>+9 Health</li>
        </ul>
      </li>

      <li class="item">
        <h2 class="item__title">Relic</h2>
        <ul class="item__list">
          <li>+22 Mana</li>
          <li>31% incr Spell Crit Strike Chance</li>
          <li>10% incr Phys Damage</li>
          <li>+7% Phys Res</li>
          <li>+5% Cold Res</li>
        </ul>
      </li>
    </ul>
  </main>
</template>

<style scoped></style>
