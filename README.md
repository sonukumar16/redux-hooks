# redux-hooks

# Hooks for React-Redux:
Redux hook API can replace the higher-order component, “connect()”, with hooks like “useSelector” and “useDispatch”. Currently, React-Redux provides 3 hooks:
* useSelector(): useSelector hook is a replacement of the mapStateToProps. It runs whenever function component renders. Its purpose is to extract data from the Redux store state.
* useDispatch(): It acts as a replacement for mapDispatchToProps. It returns to the reference to the dispatch object.
* useStore(): This returns the reference of the Redux store that was wrapped in the <provider>. It is not recommended for frequent use but can be used in scenarios like replacing reducers.