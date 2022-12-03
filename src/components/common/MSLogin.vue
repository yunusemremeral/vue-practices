<script setup>

import TKInput from "../design-system/TKInput.vue";
import TKSelect from "../design-system/TKSelect.vue";
import TKLabel from "../design-system/TKLabel.vue";
import TKCheck from "../design-system/TKCheck.vue";
import TKButton from "../design-system/TKButton.vue";
</script>

<template>
    <div class="mslogin">
        <TKLabel>
            <template #text>
                Sign-in preferences
            </template>
        </TKLabel>
        <TKSelect></TKSelect>
        <TKInput :placeholder="'Membership number'"></TKInput>
        <TKInput :placeholder="'Password'"></TKInput>
        <TKCheck :value="rememberme">
            <template #text>
                Remember me
            </template>
        </TKCheck>
        <TKButton>
            <template #text>
                Sign in
            </template>
        </TKButton>
    </div>
</template>
<style scoped>
  .mslogin{
    display: flex;
    flex-direction: column;
    width: 300px;
    background: #e9e9e9;
    padding: 25px;
  }
 

</style>