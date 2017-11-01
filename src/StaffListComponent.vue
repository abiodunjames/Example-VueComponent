<template>
    <table class="table table-bordered">
        <tbody>
        <tr v-for="staff in staffs">
            <td>{{staff.name}}</td>
            <td>{{staff.email}}</td>
            <td>{{staff.role}}</td>
        </tr>
        </tbody>
    </table>
</template>


<script>
    module.exports = {
        name: "StaffListComponent",
        data (){
            return {
                staffs: [
                    {name: 'John Doe', email: 'John.doe@acme.org', role: 'Central Executive Officer'},
                    {name: 'Rebbecca Dan', email: 'rebbecca.dan@acme.org', role: 'Backend Developer'},
                    {name: 'Tope Joshua', email: 'tope.joshua@acme.org', role: 'Financial Analyst'},
                    {name: 'Alima Fatima', email: 'alima.fatima@acme.org', role: 'Deputy CTO'},
                    {name: 'Sikiru Oluwaseun', email: 'sikiru.oluwaseun@acme.org', role: 'Project Manager'},
                    {name: 'Larry Greg', email: 'larry.greg@acme.org', role: 'Senior Developer'},
                    {name: 'Inna Brown', email: 'inna.brown@acme.org', role: 'Community Manager'},
                    {name: 'Tunde Ogundipe', email: 'tunde.ogundipe@acme.org', role: 'Chief Technology Officer'},
                    {name: 'Bald Kuma', email: 'bald.kuma@acme.org', role: 'Human Resource'},
                    {name: 'Ramon Aduragbemi', email: 'ramon.aduragbemi@acme.org', role: 'System Administrator'},
                ]
            }
        }
    }

</script>


<style scoped>
</style>