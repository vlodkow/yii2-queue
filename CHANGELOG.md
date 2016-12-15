# Change Log
All notable changes to this project will be documented in this file.

## 1.3.1 (fork)
- Added sleep for minimize server load
- Don't print to console "No Jobs"

## 1.3.0
- Added implementation for DbQueue and RedisQueue.
- Added events for queue.
- Added `purge` method for queue.
- Refactoring code.

## 1.2.3
- Passing scenario for model and active record.

## 1.2.2
- Removing deprecated method `call_user_method`.

## 1.2.1
- Added `DeferredEventTrait`

## 1.2.0
- Added tests
- Added `MemoryQueue`, `DeferredEventHandler`, and `ActiveRecordDeferredEventHandler`.

## 1.0.1

### Changed
- Refactoring controller classes to Web, Console, and Worker.

### Added
- Added Web endpoint for posting queue.

## 2015-02-25

### Changed
- Shorten  `postJob`, `getJob`, `deleteJob`, `runJob` method name to `post`,
  `fetch`, `delete`, `run`.

### Fixed
- Error when closure is not returning boolean variable.

### Added
- DeferredEventBehavior for deferring event handler to the task queue.
- Peek and Purging in the console command.
- MultipleQueue for multiple queue and priority queue.
