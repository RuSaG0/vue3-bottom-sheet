# Vue Bottom Sheet

The code was originally taken from https://github.com/vaban-ru/vue-bottom-sheet/. I can't create a pull request to this repository, because the changes of ref open/close logic to v-model leads to loss of backward compatibility

## Features

- Using v-model instead of ref & .open() .close() from parent & defineExpose() from child
- Bug fix that it is possible to reopen the modal during the close animation.
- delete from DOM while bottom sheet is hidden


## Props
All the same as https://github.com/vaban-ru/vue-bottom-sheet/, but you should use v-model instead of open()/close() methods. For example, if you have a bottom sheet for mobile layout and a typical popup for desktop layout - close/open will be very inconvenient