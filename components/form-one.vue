<template>
<div class="formgrid grid" style="width: 75%">
    <div class="field col-12 md:col-6">
        <label for="firstname6">Firstname</label>
        <input id="firstname6" type="text" class="text-base text-color surface-overlay p-2 border-1 border-solid surface-border border-round appearance-none outline-none focus:border-primary w-full">
    </div>
    <div class="field col-12 md:col-6">
        <label for="lastname6">Lastname</label>
        <input id="lastname6" type="text" class="text-base text-color surface-overlay p-2 border-1 border-solid surface-border border-round appearance-none outline-none focus:border-primary w-full">
    </div>
    <div class="field col-12">
        <label for="address">Address</label>
        <textarea id="address" type="text" rows="2" class="text-base text-color surface-overlay p-2 border-1 border-solid surface-border border-round appearance-none outline-none focus:border-primary w-full"></textarea>
    </div>
    <div class="field col-12 md:col-6">
        <label for="city">City</label>
        <input id="city" type="text" class="text-base text-color surface-overlay p-2 border-1 border-solid surface-border border-round appearance-none outline-none focus:border-primary w-full">
    </div>
    <div class="field col-12 md:col-3">
        <label for="state">State</label>
        <select id="state" class="w-full text-base text-color surface-overlay p-2 border-1 border-solid surface-border border-round outline-none focus:border-primary" style="appearance: auto">
            <option>Arizona</option>
            <option>California</option>
            <option>Florida</option>
            <option>Ohio</option>
            <option>Washington</option>
        </select>
    </div>
    <div class="field col-12 md:col-3">
        <label for="zip">Zip</label>
        <input id="zip" type="text" class="text-base text-color surface-overlay p-2 border-1 border-solid surface-border border-round appearance-none outline-none focus:border-primary w-full">
    </div>
</div>

</template>