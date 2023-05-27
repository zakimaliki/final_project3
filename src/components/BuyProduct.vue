<template>
  <div>
    <!-- Button trigger modal -->
    <button
      type="button"
      class="btn btn-primary"
      data-toggle="modal"
      data-target="#exampleModalCenter"
    >
      +
    </button>

    <!-- Modal -->
    <div
      class="modal fade"
      id="exampleModalCenter"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalCenterTitle"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h5
              class="modal-title"
              id="exampleModalLongTitle"
              style="color: black"
            >
              Buy Item
            </h5>
            <button
              type="button"
              class="x btn-danger"
              data-dismiss="modal"
              aria-label="Close-light"
            >
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <div class="choose">
              <p style="color: black">Size</p>
              <select>
                <option value="38">38</option>
                <option value="39">39</option>
                <option value="40">40</option>
                <option value="41">41</option>
                <option value="42">42</option>
                <option value="43">43</option>
                <option value="44">44</option>
              </select>
            </div>
            <div class="choose">
              <p style="color: black">Quantity</p>
              <input type="number" />
            </div>
          </div>
          <div class="modal-footer">
            <button
              type="button"
              class="cancel btn btn-danger"
              data-dismiss="modal"
            >
              Cancel
            </button>
            <button type="button" class="buy btn">Buy</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "BuyProduct",
};
</script>
<style scoped>
button {
  width: 40px;
  height: 40px;
  border-radius: 10px;
  border: none;
  color: white;
  font-family: sans-serif;
  font-weight: bold;
  background: #088178;
  outline: none;
  position: absolute;
  bottom: 20px;
  right: 10px;
}

.buy {
  width: 60px;
  height: 40px;
  color: white;
  background: #088178;
  margin-right: 90px;
}

.cancel {
  width: 80px;
}

.x {
  width: 40px;
  height: 40px;
  margin-bottom: 185px;
}

input {
  width: 50px;
  border-radius: 5px;
  border: 1.5px solid lightgray;
}

.choose {
  line-height: 0.5px;
  margin-bottom: 30px;
}
</style>
