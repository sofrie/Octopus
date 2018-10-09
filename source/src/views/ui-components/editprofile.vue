<template lang="html">
  <section class="editprofile">
    <h1 align="center">Welcome, Richard V.Welsh</h1>
    <table align="center">
        <tr>
            <td> <h2 class="mt-2 text-success font-weight-bold">Your profile</h2> </td>
        </tr>
        <tr>
            <td> <h2 class="mt-2 text-info font-weight-bold">now is ready</h2> </td>
        </tr>
        <tr>
            <td> <h2 class="mt-2 text-info font-weight-bold">to do any changes</h2> </td>
        </tr>
    </table>
    <div align="center">
        <div class="profile-image"> 
            <img src="../../assets/images/faces/face4.jpg" alt="image"/> 
        </div>
        <div>
            <button>Choose profile picture</button>
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
                <td><input type="text" placeholder="Email" value="richard@company.com"/></td>                
            </tr>
            <tr>
                <td><h3>Phone Number</h3></td>
                <td><h3>:</h3></td>
                <td><input type="text" placeholder="Phone Number" value="+81 3-3770-2301"/>"</td>                
            </tr>
             <tr>
                <td><h3>Address</h3></td>
                <td><h3>:</h3></td>
                <td><input type="text" placeholder="Address" value="Udagawacho, Shibuya, Tokyo 150-0042, Japan"/></td>                
            </tr>
             <tr>
                <td><h3>About</h3></td>
                <td><h3>:</h3></td>
                <td><input type="text" placeholder="About" value="it's personal, myself and I"/></td>                
            </tr>
            <tr>
                <td colspan="3" align="center">
                    <button class="btn btn-fw btn-warning">Save Changes</button>
                    <a href="/profile" class="btn btn-fw btn-danger">Cancel</a>
                </td>
            </tr>
        </table>
    </div>
  </section>
</template>

<script lang="js">
export default {
  name: 'editprofile'
}
</script>

<style scoped lang="scss">
.editprofile {

}
</style>
