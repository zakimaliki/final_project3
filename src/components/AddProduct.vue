<template>
  <div>
    <div class="container">
      <b-button @click="$bvModal.show('modal-scoped')" variant="success" class="btn-add">Add Items</b-button>

      <b-modal id="modal-scoped">
        <template #modal-header="{ close }">
          <b-button size="sm" variant="outline-danger" @click="close()">
            X
          </b-button>
        </template>

        <template>
            <div class="add">
              <p class="enter">Enter Shoes</p>
              <input type="text" placeholder="Enter Shoes" />
            </div>
            <div class="add"><hr /></div>
            <div class="add">
              <p class="enter">Enter Price</p>
              <input type="text" placeholder="Enter Price" />
            </div>
        </template>

        <template #modal-footer="{  cancel }">
          <b-button size="sm" variant="success" @click.prevent="createData"> Add Items </b-button>
          <b-button size="sm" variant="danger" @click="cancel()">
            Cancel
          </b-button>
        </template>
      </b-modal>
    </div>
  </div>
</template>
<script>
export default {
  name: "ModalButton",
  data() {
    return {
    };
  },
  methods: {
  },
};
</script>
<style scoped>
.btn-add {
  float: left;
  width: 120px;
  height: 40px;
  border-radius: 10px;
  border: none;
  color: white;
  font-family: sans-serif;
  font-weight: bold;
  background: #088178;
  outline: none;
}

.x {
  width: 40px;
  height: 40px;
}
</style>
