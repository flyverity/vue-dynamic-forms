<template>
  <input
    :id="formControl.id"
    v-model="formControl.value"
    :name="formControl.name"
    class="form-control"
    :type="formControl.type"
    :placeholder="formControl.placeholder"
    :disabled="formControl.disabled"
    @change="valueChange()"
    @focus="onFocus()"
    @blur="onBlur()"
  />
</template>
<script src="./InputText.js"></script>
