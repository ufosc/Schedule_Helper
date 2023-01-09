<script>
    function addSelection(addSelectionButton) {
        let courseSelections = addSelectionButton.parent.querySelector("#add-selection");
        console.log(courseSelections);
    }
</script>

<div class="inline-block p-2 ml-2 bg-slate-100">
    <div id="course-selections"></div>

    <button id="add-selection" onclick="addSelection(this)">Add a Selection</button>
</div>
