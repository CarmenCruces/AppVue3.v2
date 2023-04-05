<script>
import ComputedProps from './components/myComponents/computed-properties/ComputedProps.vue';
import DirectiveVFor from './components/myComponents/directives/DirectiveVFor.vue';
import DirectiveVif from './components/myComponents/directives/DirectiveVif.vue';
import DirectiveVModel from './components/myComponents/directives/DirectiveVModel.vue';
import DirectiveVShow from './components/myComponents/directives/DirectiveVShow.vue';
import ParentComponent from './components/myComponents/props/ParentComponent.vue';
import SingleComponent from './components/myComponents/SingleComponent.vue';
import RawHtmlData from './components/myComponents/RawHtmlData.vue';
export default {
    components: {SingleComponent, RawHtmlData, DirectiveVShow, DirectiveVif, DirectiveVModel, DirectiveVFor, ComputedProps, ParentComponent},
};

</script>

<template>
    <div>
        <h1>My Single Page</h1>
        <h3>Lorem ipsum dolor, sit amet consectetur adipisicing elit....</h3>
        -----------------------------------------------------------------
        <RawHtmlData /> 
        -----------------------------------------------------------------
        <SingleComponent />
        -----------------------------------------------------------------
        <DirectiveVShow />
        -----------------------------------------------------------------
        <DirectiveVif />
        -----------------------------------------------------------------
        <DirectiveVModel />
        -----------------------------------------------------------------
        <DirectiveVFor />
        -----------------------------------------------------------------
        <ComputedProps />
        -----------------------------------------------------------------
        <ParentComponent />
        -----------------------------------------------------------------
    </div>
</template>

<style lang="css" scoped>
h1{
    color: rgb(137, 44, 44);
}
</style>