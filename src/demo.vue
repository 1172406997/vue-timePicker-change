<style scoped>

</style>

<template>
    <datepicker ></datepicker>
    <!--<datepicker format="YYYY-M-D" value="2015-9-5"></datepicker>
    <datepicker :readonly="true" format="MMM/D/YYYY" width="300px" name="date"></datepicker>-->
</template>

<script>
import datepicker from './datepicker.vue';

export default {
    components: { datepicker }
};
</script>

