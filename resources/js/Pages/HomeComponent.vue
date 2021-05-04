<template>
  <div>
      <Layout title="Welcome">
          <UserTable></UserTable>
      </Layout>

  </div>
</template>
// 
 import UserTable from './../../UsersTableComponent.vue
<script>
 import Layout from './Layout';
  import UserTable from '../Components/Table/UsersTableComponent'
export default {
     components: {
      Layout,
      UserTable,
    },
}
</script>

<style>

</style>
