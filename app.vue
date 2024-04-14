<template>
  <div>
    <FormKit
        label="Username"
        name="username"
        type="text"
        help="Pick a new username"
        validation="required|matches:/^@{a-zA-Z]+$/|length:5"
        value="@useFromKit"
        prefix-icon="avatarMan"
    />
    <FormKit type="text"/>
    <FormKit type="select"/>
    <FormKit type="textarea"/>
  </div>
</template>
