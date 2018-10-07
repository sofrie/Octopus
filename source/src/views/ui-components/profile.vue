<template lang="html">

  <section class="profile">
    <h1 align="center">Welcome, Richard V.Welsh</h1>
    <table align="center">
        <tr>
            <td> <h2 class="mt-2 text-success font-weight-bold">Something</h2> </td>
        </tr>
        <tr>
            <td> <h2 class="mt-2 text-info font-weight-bold">to do with</h2> </td>
        </tr>
        <tr>
            <td> <h2 class="mt-2 text-info font-weight-bold">your profile?</h2> </td>
        </tr>
    </table>
    <div align="center">
        <div class="profile-image"> 
            <img src="../../assets/images/faces/face4.jpg" alt="image"/> 
        </div>
        <div class="profile-name">
            <p class="name"><b>Richard V.Welsh</b></p>
            <p class="designation text-success font-weight-bold">Manager</p>
        </div>
    </div>
    <div align="center">
        <table>
            <tr>
                <td><h3>Email</h3></td>
                <td><h3>:</h3></td>
                <td><h3>richard@company.com</h3></td>                
            </tr>
            <tr>
                <td><h3>Phone Number</h3></td>
                <td><h3>:</h3></td>
                <td><h3>+81 3-3770-2301</h3></td>                
            </tr>
             <tr>
                <td><h3>Address</h3></td>
                <td><h3>:</h3></td>
                <td><h3>Udagawacho, Shibuya, Tokyo 150-0042, Japan</h3></td>                
            </tr>
             <tr>
                <td><h3>About</h3></td>
                <td><h3>:</h3></td>
                <td><h3>it's personal, myself and I</h3></td>                
            </tr>
            <tr>
                <td colspan="3" align="center">
                    <button class="btn btn-fw btn-warning">Edit Your Profile</button>
                    <button class="btn btn-fw btn-warning">Change Your Password</button>
                </td>
            </tr>
        </table>
    </div>
  </section>

</template>

<script lang="js">
export default {
  name: 'profile'
}
</script>

<style scoped lang="scss">
.profile {

}
</style>
