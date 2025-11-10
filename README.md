# add-function-reset-draft-1
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
