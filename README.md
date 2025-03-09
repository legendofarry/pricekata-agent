# productly

<select onchange="updateStatus(${index}, this.value)">
                <option value="Pending" ${order.status === "Pending" ? "selected" : ""
          }>Pending</option>
                <option value="Delivered" ${order.status === "Delivered" ? "selected" : ""
          }>Delivered</option>
                <option value="Paid" ${order.status === "Paid" ? "selected" : ""
          }>Paid</option>
                </select>
