<template>
  <BaseLayout>
    <div style="margin: 60px auto;max-width:600px">
      <h1>Contact</h1>
      <table>
        <tbody>
          <tr>
            <td>
              <IconBase name="mail">
                <img svg-inline src="@lipsurf/common/assets/icons/mail-outline.svg" />
              </IconBase>
            </td>
            <td><a href="mailto:help@lipsurf.com">help@lipsurf.com</a></td>
          </tr>
          <tr>
            <td>
              <IconBase name="chat">
                <img svg-inline src="@lipsurf/common/assets/icons/comment.svg" />
              </IconBase>
            </td>
            <td><a href="https://discuss.lipsurf.com">Forums</a></td>
          </tr>
          <tr>
            <td>
              <IconBase name="phone">
                <img svg-inline src="@lipsurf/common/assets/icons/phone.svg" />
              </IconBase>
            </td>
            <td>
              Please contact us via email first to receive phone or video call
              support.
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </BaseLayout>
</template>

<style scoped>
td .icon {
  color: var(--text-color);
  width: 25px;
  height: 25px;
}
table {
  margin: 0 auto;
}
td {
  padding: 1em;
}
</style>

<script lang="ts" setup>
import BaseLayout from "./BaseLayout.vue";
import { IconBase } from "@lipsurf/common/components";
</script>

