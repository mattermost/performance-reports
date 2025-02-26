### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 2ms | 9ms | 7ms | 290.87
| ChannelStore.GetTeamChannels | avg | 23ms | 45ms | 22ms | 93.81
| PostStore.GetPostReminders | avg | 5ms | 7ms | 2ms | 43.73
| ChannelStore.UpdateSidebarCategories | avg | 18ms | 20ms | 2ms | 10.96
| UserStore.Count | avg | 60ms | 62ms | 2ms | 3.34
| UserStore.Save | avg | 69ms | 71ms | 2ms | 2.92
| PostStore.AnalyticsPostCount | avg | 577ms | 590ms | 13ms | 2.25
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 5ms | 143ms | 138ms | 2697.73
| PostStore.GetPostReminders | p99 | 10ms | 46ms | 36ms | 370.50
| ChannelStore.GetChannelsByUser | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.UpdateOptimistically | p99 | 5ms | 18ms | 13ms | 262.63
| PostStore.SearchPostsForUser | p99 | 372ms | 1.327s | 955ms | 256.41
| ClusterDiscoveryStore.SetLastPingAt | p99 | 5ms | 13ms | 8ms | 161.62
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 23ms | 13ms | 131.31
| JobStore.Get | p99 | 8ms | 18ms | 10ms | 130.72
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.81
| FileInfoStore.GetByIds | p99 | 5ms | 9ms | 4ms | 76.92
| JobStore.UpdateStatus | p99 | 5ms | 8ms | 3ms | 60.61
| PostPriorityStore.GetForPost | p99 | 5ms | 8ms | 3ms | 60.15
| PostAcknowledgementStore.GetForPost | p99 | 5ms | 8ms | 3ms | 60.15
| DraftStore.GetDraftsForUser | p99 | 5ms | 7ms | 2ms | 40.00
| UserStore.GetUnreadCount | p99 | 16ms | 22ms | 6ms | 37.06
| ThreadStore.GetThreadFollowers | p99 | 6ms | 8ms | 2ms | 34.06
| ChannelStore.GetMemberLastViewedAt | p99 | 7ms | 9ms | 2ms | 29.41
| ChannelStore.GetGuestCount | p99 | 11ms | 14ms | 3ms | 28.02
| StatusStore.Get | p99 | 7ms | 9ms | 2ms | 27.01
| ProductNoticesStore.View | p99 | 59ms | 69ms | 10ms | 16.89
| PreferenceStore.Save | p99 | 21ms | 24ms | 3ms | 13.96
| SessionStore.Get | p99 | 17ms | 19ms | 2ms | 11.52
| ChannelStore.CreateInitialSidebarCategories | p99 | 38ms | 42ms | 4ms | 10.46
| ChannelStore.SaveMember | p99 | 49ms | 53ms | 4ms | 8.12
| ChannelStore.GetTeamChannels | p99 | 48ms | 50ms | 2ms | 4.17
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -103.87
| ChannelStore.CreateSidebarCategory | avg | 12ms | 0s | -12ms | -99.84
| TeamStore.GetActiveMemberCount | avg | 99ms | 0s | -99ms | -99.69
| TeamStore.GetTotalMemberCount | avg | 75ms | 0s | -75ms | -99.55
| ChannelStore.Save | avg | 11ms | 9ms | -2ms | -18.07
| ChannelStore.AutocompleteInTeamForSearch | avg | 243ms | 225ms | -18ms | -7.40
| UserStore.AutocompleteUsersInChannel | avg | 129ms | 125ms | -4ms | -3.11
| UserStore.GetAllProfilesInChannel | avg | 196ms | 191ms | -5ms | -2.55
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| TeamStore.GetTotalMemberCount | p99 | 100ms | 0s | -100ms | -100.50
| TeamStore.GetActiveMemberCount | p99 | 244ms | 0s | -244ms | -100.00
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 22ms | 5ms | -17ms | -75.72
| ChannelBookmarkStore.Save | p99 | 24ms | 10ms | -14ms | -58.62
| UserStore.GetByUsername | p99 | 19ms | 8ms | -11ms | -57.89
| JobStore.GetCountByStatusAndType | p99 | 38ms | 18ms | -20ms | -52.98
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 5ms | -5ms | -52.08
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.51
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.96
| JobStore.UpdateStatusOptimistically | p99 | 8ms | 5ms | -3ms | -39.22
| UserStore.Update | p99 | 8ms | 5ms | -3ms | -38.96
| PostStore.GetPostsAfter | p99 | 8ms | 5ms | -3ms | -36.59
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 91ms | 62ms | -29ms | -31.91
| ChannelStore.GetPublicChannelsForTeam | p99 | 24ms | 19ms | -5ms | -20.65
| ThreadStore.GetTeamsUnreadForUser | p99 | 12ms | 10ms | -2ms | -17.32
| PreferenceStore.GetAll | p99 | 16ms | 14ms | -2ms | -12.29
| ChannelStore.Save | p99 | 48ms | 43ms | -5ms | -10.35
| UserStore.AutocompleteUsersInChannel | p99 | 359ms | 326ms | -33ms | -9.19
| PostStore.Delete | p99 | 25ms | 23ms | -2ms | -8.10
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.309s | 2.276s | -33ms | -1.43
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createDirectChannel | avg | 134ms | 158ms | 24ms | 17.87
| deletePost | avg | 13ms | 15ms | 2ms | 15.57
| createGroupChannel | avg | 204ms | 219ms | 15ms | 7.37
| updateCategoriesForTeamForUser | avg | 28ms | 30ms | 2ms | 7.03
| getProfileImage | avg | 68ms | 71ms | 3ms | 4.38
| createUser | avg | 101ms | 105ms | 4ms | 3.97
| addChannelMember | avg | 141ms | 145ms | 4ms | 2.84
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelsForUser | p99 | 5ms | 21ms | 16ms | 323.23
| searchPostsInTeam | p99 | 482ms | 1.327s | 845ms | 175.39
| getClientConfig | p99 | 14ms | 18ms | 4ms | 27.99
| getProfileImage | p99 | 275ms | 347ms | 72ms | 26.16
| getUsers | p99 | 12ms | 15ms | 3ms | 25.21
| getUser | p99 | 13ms | 15ms | 2ms | 15.45
| getPostsForChannel | p99 | 122ms | 140ms | 18ms | 14.78
| getFilePreview | p99 | 95ms | 97ms | 2ms | 2.11
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 15ms | 0s | -15ms | -102.95
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -100.73
| getTeamStats | avg | 99ms | 0s | -99ms | -99.61
| setPostReminder | avg | 19ms | 14ms | -5ms | -26.57
| createChannel | avg | 191ms | 165ms | -26ms | -13.59
| autocompleteChannelsForTeamForSearch | avg | 243ms | 225ms | -18ms | -7.40
| autocompleteUsers | avg | 114ms | 109ms | -5ms | -4.38
| createPost | avg | 153ms | 149ms | -4ms | -2.62
| uploadFileStream | avg | 399ms | 395ms | -4ms | -1.00
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| getTeamStats | p99 | 244ms | 0s | -244ms | -100.00
| setPostReminder | p99 | 49ms | 25ms | -24ms | -48.73
| unfollowThreadByUser | p99 | 44ms | 24ms | -20ms | -45.71
| getPublicChannelsForTeam | p99 | 24ms | 19ms | -5ms | -20.52
| autocompleteUsers | p99 | 324ms | 273ms | -51ms | -15.73
| getPreferences | p99 | 17ms | 15ms | -2ms | -11.45
| addTeamMember | p99 | 1.859s | 1.799s | -60ms | -3.23
| autocompleteChannelsForTeamForSearch | p99 | 2.309s | 2.276s | -33ms | -1.43
| createPost | p99 | 825ms | 816ms | -9ms | -1.09
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.956
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 7ms| 6ms | -1ms | -13.922
| |  P99| 24ms| 10ms | -14ms | -58.619
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 954ms| 958ms | 4ms | 0.419
| |  P99| 2.46s| 2.461s | 1ms | 0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 243ms| 225ms | -18ms | -7.402
| |  P99| 2.309s| 2.276s | -33ms | -1.429
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 38ms| 42ms | 4ms | 10.457
| ChannelStore.CreateSidebarCategory |  Avg| 12ms| 0s | -12ms | -99.837
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 2ms | -1ms | -37.962
| |  P99| 10ms| 9ms | -1ms | -10.490
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 91ms| 62ms | -29ms | -31.911
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.978
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 3ms | 1ms | 44.823
| |  P99| 5ms| 21ms | 16ms | 323.232
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.291
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 14ms | 3ms | 28.020
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.566
| ChannelStore.GetMemberCount |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 245ms| 245ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 29.409
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.010
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 8ms | -1ms | -11.598
| |  P99| 24ms| 19ms | -5ms | -20.651
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 23ms| 45ms | 22ms | 93.811
| |  P99| 48ms| 50ms | 2ms | 4.166
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 9ms | -2ms | -18.071
| |  P99| 48ms| 43ms | -5ms | -10.347
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 49ms| 53ms | 4ms | 8.124
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 18ms| 20ms | 2ms | 10.961
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 3ms | 1ms | 43.071
| |  P99| 5ms| 13ms | 8ms | 161.616
| CommandWebhookStore.Cleanup |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.505
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 6ms| 7ms | 1ms | 17.239
| |  P99| 10ms| 23ms | 13ms | 131.313
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 3ms | 1ms | 40.153
| |  P99| 5ms| 7ms | 2ms | 40.002
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 76.923
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.410
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.440
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 3ms | 1ms | 44.714
| |  P99| 8ms| 18ms | 10ms | 130.719
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.597
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -32.468
| |  P99| 38ms| 18ms | -20ms | -52.980
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 2ms| 3ms | 1ms | 42.986
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.216
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.639
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.147
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.147
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 577ms| 590ms | 13ms | 2.253
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 23ms | -2ms | -8.097
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 3ms | 1ms | 45.636
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostReminders |  Avg| 5ms| 7ms | 2ms | 43.732
| |  P99| 10ms| 46ms | 36ms | 370.497
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.588
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.426
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 41ms| 40ms | -1ms | -2.444
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 60ms| 60ms | 0s | 0.000
| |  P99| 372ms| 1.327s | 955ms | 256.410
| PostStore.SetPostReminder |  Avg| 3ms| 4ms | 1ms | 28.808
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 10ms| 11ms | 1ms | 9.622
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.292
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 13.956
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 16ms| 17ms | 1ms | 6.325
| |  P99| 59ms| 69ms | 10ms | 16.892
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.790
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 1ms | -1ms | -53.152
| |  P99| 22ms| 5ms | -17ms | -75.724
| SessionStore.Get |  Avg| 3ms| 4ms | 1ms | 28.599
| |  P99| 17ms| 19ms | 2ms | 11.522
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.016
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 3ms | 1ms | 40.346
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.163
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.005
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 2ms| 9ms | 7ms | 290.868
| |  P99| 5ms| 143ms | 138ms | 2697.729
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 99ms| 0s | -99ms | -99.689
| |  P99| 244ms| 0s | -244ms | -99.998
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 3ms | 1ms | 41.037
| |  P99| 9ms| 10ms | 1ms | 11.521
| TeamStore.GetMember |  Avg| 1ms| 2ms | 1ms | 67.534
| |  P99| 5ms| 6ms | 1ms | 18.191
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.312
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.154
| TeamStore.GetTotalMemberCount |  Avg| 75ms| 0s | -75ms | -99.554
| |  P99| 100ms| 0s | -100ms | -100.503
| TeamStore.SaveMember |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.322
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 34.061
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.050
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.044
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.411
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 2ms | 1ms | 69.802
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -103.874
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 129ms| 125ms | -4ms | -3.110
| |  P99| 359ms| 326ms | -33ms | -9.190
| UserStore.Count |  Avg| 60ms| 62ms | 2ms | 3.339
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.258
| UserStore.GetAllProfilesInChannel |  Avg| 196ms| 191ms | -5ms | -2.546
| |  P99| 495ms| 494ms | -1ms | -0.202
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 8ms | -11ms | -57.895
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.083
| UserStore.GetUnreadCount |  Avg| 6ms| 5ms | -1ms | -17.637
| |  P99| 16ms| 22ms | 6ms | 37.063
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 71ms | 2ms | 2.916
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 58ms| 57ms | -1ms | -1.732
| |  P99| 241ms| 240ms | -1ms | -0.414
| UserStore.Update |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.960
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.906
| UserStore.UpdateLastLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.479
| UserStore.UpdateUpdateAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.372
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 141ms| 145ms | 4ms | 2.841
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 631ms| 633ms | 2ms | 0.317
| | P99| 1.859s| 1.799s | -60ms | -3.228
| autocompleteChannelsForTeamForSearch | Avg| 243ms| 225ms | -18ms | -7.401
| | P99| 2.309s| 2.276s | -33ms | -1.429
| autocompleteUsers | Avg| 114ms| 109ms | -5ms | -4.384
| | P99| 324ms| 273ms | -51ms | -15.729
| createCategoryForTeamForUser | Avg| 15ms| 0s | -15ms | -102.947
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 191ms| 165ms | -26ms | -13.594
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 11ms| 10ms | -1ms | -9.349
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 134ms| 158ms | 24ms | 17.868
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 204ms| 219ms | 15ms | 7.371
| | P99| 489ms| 489ms | 0s | 0.000
| createPost | Avg| 153ms| 149ms | -4ms | -2.619
| | P99| 825ms| 816ms | -9ms | -1.090
| createUser | Avg| 101ms| 105ms | 4ms | 3.971
| | P99| 246ms| 247ms | 1ms | 0.407
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 7ms | 1ms | 17.715
| deletePost | Avg| 13ms| 15ms | 2ms | 15.567
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 12ms | 1ms | 8.781
| getCategoriesForTeamForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannel | Avg| 4ms| 5ms | 1ms | 22.639
| | P99| 9ms| 10ms | 1ms | 10.541
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 207ms| 206ms | -1ms | -0.484
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 3ms | 1ms | 43.535
| | P99| 5ms| 21ms | 16ms | 323.232
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 14ms| 18ms | 4ms | 27.992
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.018
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 95ms| 97ms | 2ms | 2.109
| getFileThumbnail | Avg| 31ms| 32ms | 1ms | 3.175
| | P99| 88ms| 88ms | 0s | 0.000
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 18ms| 19ms | 1ms | 5.510
| | P99| 122ms| 140ms | 18ms | 14.780
| getPostsForChannelAroundLastUnread | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getPreferences | Avg| 4ms| 3ms | -1ms | -28.452
| | P99| 17ms| 15ms | -2ms | -11.455
| getProfileImage | Avg| 68ms| 71ms | 3ms | 4.385
| | P99| 275ms| 347ms | 72ms | 26.161
| getPublicChannelsForTeam | Avg| 10ms| 9ms | -1ms | -10.448
| | P99| 24ms| 19ms | -5ms | -20.517
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 15ms | -1ms | -6.280
| getTeamStats | Avg| 99ms| 0s | -99ms | -99.606
| | P99| 244ms| 0s | -244ms | -99.998
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.165
| getTeamsUnreadForUser | Avg| 4ms| 5ms | 1ms | 23.170
| | P99| 19ms| 19ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 13.517
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 15ms | 2ms | 15.453
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 15ms | 3ms | 25.208
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 3ms | 1ms | 40.163
| | P99| 7ms| 7ms | 0s | 0.000
| login | Avg| 53ms| 54ms | 1ms | 1.903
| | P99| 238ms| 240ms | 2ms | 0.841
| logout | Avg| 17ms| 18ms | 1ms | 5.999
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| removeUserCustomStatus | Avg| 91ms| 92ms | 1ms | 1.103
| | P99| 245ms| 245ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| searchAllChannels | Avg| 954ms| 959ms | 5ms | 0.524
| | P99| 2.46s| 2.461s | 1ms | 0.041
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 66ms| 65ms | -1ms | -1.526
| | P99| 482ms| 1.327s | 845ms | 175.392
| searchUsers | Avg| 59ms| 58ms | -1ms | -1.707
| | P99| 242ms| 241ms | -1ms | -0.414
| setPostReminder | Avg| 19ms| 14ms | -5ms | -26.575
| | P99| 49ms| 25ms | -24ms | -48.730
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 44ms| 24ms | -20ms | -45.711
| updateCategoriesForTeamForUser | Avg| 28ms| 30ms | 2ms | 7.030
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -100.731
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 399ms| 395ms | -4ms | -1.001
| | P99| 987ms| 987ms | 0s | 0.000
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| viewChannel | Avg| 10ms| 11ms | 1ms | 9.546
| | P99| 25ms| 25ms | 0s | 0.000
