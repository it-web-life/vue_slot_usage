<template>
  <div class="block">
    <!-- defaultのslotしかない場合のみ、templateを省略して親コンポーネントにv-slotを書くことができる -->
    <ExampleChild v-slot="slotProps">
      <h3>Example６: スロットプロパティのdefaultは省略できる</h3>
      <p>こんにちは、{{ slotProps.user.lastName }} {{ slotProps.user.firstName }}さん</p>
      <p>年齢：{{ slotProps.age }}歳</p>
    </ExampleChild>

    <!-- <ExampleChild v-slot:default="slotProps">
      <h3>Example6: スロットプロパティのdefaultは省略できる</h3>
      <p>こんにちは、{{ slotProps.user.lastName }} {{ slotProps.user.firstName }}さん</p>
      <p>年齢：{{ slotProps.age }}歳</p>
    </ExampleChild> -->

    <!-- <ExampleChild>
      <template v-slot:default="slotProps">
        <h3>Example6: スロットプロパティのdefaultは省略できる</h3>
        <p>こんにちは、{{ slotProps.user.lastName }} {{ slotProps.user.firstName }}さん</p>
        <p>年齢：{{ slotProps.age }}歳</p>
      </template>
    </ExampleChild> -->
  </div>
</template>

<script>
import ExampleChild from './ExampleChild.vue'

export default {
  name: 'Example',
  components: {
    ExampleChild
  }
}
</script>
