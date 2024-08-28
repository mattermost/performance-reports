### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 11ms | 11ms | 3802035.68
| SessionStore.Remove | avg | 3ms | 7ms | 4ms | 158.46
| ThreadStore.MarkAllAsReadByChannels | avg | 1ms | 3ms | 2ms | 138.64
| JobStore.GetCountByStatusAndType | avg | 2ms | 4ms | 2ms | 105.82
| JobStore.Save | avg | 3ms | 5ms | 2ms | 62.07
| ChannelStore.GetSidebarCategory | avg | 19ms | 24ms | 5ms | 25.76
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 24ms | 27ms | 3ms | 12.65
| UserStore.GetProfilesInChannel | avg | 17ms | 19ms | 2ms | 11.74
| TeamStore.GetActiveMemberCount | avg | 60ms | 65ms | 5ms | 8.39
| ChannelStore.AutocompleteInTeamForSearch | avg | 78ms | 84ms | 6ms | 7.67
| UserStore.GetAllProfilesInChannel | avg | 260ms | 263ms | 3ms | 1.15
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SessionStore.Remove | p99 | 5ms | 48ms | 43ms | 868.69
| RoleStore.GetByNames | p99 | 5ms | 48ms | 43ms | 868.69
| JobStore.GetCountByStatusAndType | p99 | 5ms | 44ms | 39ms | 787.88
| ThreadStore.MarkAllAsReadByChannels | p99 | 5ms | 43ms | 38ms | 767.68
| JobStore.Save | p99 | 18ms | 77ms | 59ms | 328.69
| TeamStore.GetTotalMemberCount | p99 | 99ms | 243ms | 144ms | 145.09
| UserStore.Update | p99 | 35ms | 85ms | 50ms | 141.15
| ChannelStore.Save | p99 | 63ms | 148ms | 85ms | 135.98
| ChannelStore.GetPinnedPostCount | p99 | 9ms | 20ms | 11ms | 119.79
| PluginStore.List | p99 | 20ms | 41ms | 21ms | 107.13
| FileInfoStore.AttachToPost | p99 | 23ms | 44ms | 21ms | 90.00
| RoleStore.ChannelHigherScopedPermissions | p99 | 24ms | 44ms | 20ms | 84.14
| PostAcknowledgementStore.GetForPost | p99 | 22ms | 33ms | 11ms | 49.50
| JobStore.GetNewestJobByStatusesAndType | p99 | 26ms | 38ms | 12ms | 47.06
| FileInfoStore.Save | p99 | 24ms | 34ms | 10ms | 41.41
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.725s | 3.567s | 842ms | 30.90
| ClusterDiscoveryStore.SetLastPingAt | p99 | 43ms | 56ms | 13ms | 29.89
| ChannelStore.GetAllChannelMembersForUser | p99 | 33ms | 42ms | 9ms | 27.64
| FileInfoStore.Get | p99 | 15ms | 19ms | 4ms | 26.92
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 226ms | 280ms | 54ms | 23.87
| ReactionStore.GetForPost | p99 | 19ms | 23ms | 4ms | 20.62
| StatusStore.GetByIds | p99 | 19ms | 22ms | 3ms | 15.99
| ChannelStore.GetSidebarCategory | p99 | 202ms | 227ms | 25ms | 12.38
| GroupStore.GetGroups | p99 | 25ms | 28ms | 3ms | 12.15
| ChannelStore.GetChannels | p99 | 25ms | 28ms | 3ms | 12.07
| ChannelStore.GetMemberLastViewedAt | p99 | 35ms | 39ms | 4ms | 11.44
| FileInfoStore.SetContent | p99 | 44ms | 49ms | 5ms | 11.25
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 18ms | 20ms | 2ms | 11.04
| PostStore.GetSingle | p99 | 18ms | 20ms | 2ms | 10.93
| LinkMetadataStore.Get | p99 | 19ms | 21ms | 2ms | 10.29
| SessionStore.GetLRUSessions | p99 | 30ms | 33ms | 3ms | 9.97
| UserStore.UpdateUpdateAt | p99 | 30ms | 33ms | 3ms | 9.95
| DraftStore.Upsert | p99 | 25ms | 27ms | 2ms | 7.94
| TeamStore.GetTeamsByUserId | p99 | 38ms | 41ms | 3ms | 7.84
| ChannelStore.GetFileCount | p99 | 26ms | 28ms | 2ms | 7.83
| UserStore.UpdateLastLogin | p99 | 26ms | 28ms | 2ms | 7.65
| ThreadStore.GetTeamsUnreadForUser | p99 | 41ms | 44ms | 3ms | 7.23
| PostAcknowledgementStore.GetForPosts | p99 | 30ms | 32ms | 2ms | 6.74
| PostStore.GetPostIdAfterTime | p99 | 30ms | 32ms | 2ms | 6.68
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 154ms | 164ms | 10ms | 6.49
| ThreadStore.GetTotalThreads | p99 | 32ms | 34ms | 2ms | 6.16
| PostStore.GetEtag | p99 | 33ms | 35ms | 2ms | 6.00
| TeamStore.SaveMember | p99 | 155ms | 164ms | 9ms | 5.80
| SessionStore.Get | p99 | 73ms | 77ms | 4ms | 5.51
| UserStore.UpdateFailedPasswordAttempts | p99 | 37ms | 39ms | 2ms | 5.42
| TeamStore.GetAllPage | p99 | 39ms | 41ms | 2ms | 5.11
| PreferenceStore.GetAll | p99 | 42ms | 44ms | 2ms | 4.71
| ChannelStore.GetGuestCount | p99 | 43ms | 45ms | 2ms | 4.65
| ChannelStore.GetMemberCount | p99 | 87ms | 90ms | 3ms | 3.43
| TeamStore.GetActiveMemberCount | p99 | 237ms | 243ms | 6ms | 2.54
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | avg | 34ms | 0s | -34ms | -101.48
| PostStore.GetPostReminders | avg | 5ms | 3ms | -2ms | -37.59
| PostStore.GetPostsByThread | avg | 6ms | 4ms | -2ms | -33.53
| ThreadStore.GetThreadUnreadReplyCount | avg | 7ms | 5ms | -2ms | -29.93
| ChannelStore.UpdateSidebarCategories | avg | 90ms | 69ms | -21ms | -23.43
| PostStore.Update | avg | 13ms | 11ms | -2ms | -15.92
| TeamStore.GetTotalMemberCount | avg | 50ms | 43ms | -7ms | -13.93
| ChannelStore.GetTeamChannels | avg | 22ms | 20ms | -2ms | -8.97
| UserStore.AutocompleteUsersInChannel | avg | 48ms | 46ms | -2ms | -4.15
| PostStore.SearchPostsForUser | avg | 164ms | 160ms | -4ms | -2.43
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 0s | -50ms | -100.50
| PostStore.GetPostReminders | p99 | 46ms | 9ms | -37ms | -80.87
| PostPersistentNotificationStore.DeleteExpired | p99 | 43ms | 9ms | -34ms | -79.53
| ChannelStore.UpdateSidebarCategories | p99 | 920ms | 227ms | -693ms | -75.33
| PostStore.GetPostReminderMetadata | p99 | 23ms | 9ms | -14ms | -60.32
| JobStore.Get | p99 | 38ms | 18ms | -20ms | -52.63
| JobStore.UpdateStatusOptimistically | p99 | 38ms | 18ms | -20ms | -52.63
| PostPersistentNotificationStore.Get | p99 | 43ms | 21ms | -22ms | -51.46
| JobStore.UpdateStatus | p99 | 18ms | 9ms | -9ms | -50.56
| JobStore.UpdateOptimistically | p99 | 18ms | 9ms | -9ms | -50.56
| PostStore.Update | p99 | 50ms | 25ms | -25ms | -50.08
| PostPriorityStore.GetForPost | p99 | 57ms | 29ms | -28ms | -49.34
| ChannelStore.GetTeamChannels | p99 | 96ms | 49ms | -47ms | -49.21
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 7ms | 5ms | -2ms | -29.08
| ThreadStore.Get | p99 | 7ms | 5ms | -2ms | -28.78
| TeamStore.GetMember | p99 | 9ms | 7ms | -2ms | -22.29
| PluginStore.SetWithOptions | p99 | 47ms | 40ms | -7ms | -15.01
| ThreadStore.UpdateMembership | p99 | 14ms | 12ms | -2ms | -14.38
| DraftStore.GetDraftsForUser | p99 | 36ms | 31ms | -5ms | -14.00
| PostStore.GetPostsByThread | p99 | 25ms | 22ms | -3ms | -12.20
| UserStore.Get | p99 | 17ms | 15ms | -2ms | -11.68
| ChannelStore.GetMember | p99 | 45ms | 40ms | -5ms | -11.18
| DraftStore.Delete | p99 | 19ms | 17ms | -2ms | -10.73
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 30ms | 27ms | -3ms | -10.10
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 50ms | 45ms | -5ms | -10.08
| ThreadStore.GetThreadForUser | p99 | 41ms | 37ms | -4ms | -9.66
| JobStore.GetAllByStatus | p99 | 43ms | 39ms | -4ms | -9.35
| UserStore.AutocompleteUsersInChannel | p99 | 363ms | 334ms | -29ms | -7.99
| UserStore.GetProfileByIds | p99 | 32ms | 30ms | -2ms | -6.22
| StatusStore.SaveOrUpdate | p99 | 384ms | 361ms | -23ms | -6.00
| StatusStore.Get | p99 | 36ms | 34ms | -2ms | -5.55
| PostStore.Save | p99 | 82ms | 80ms | -2ms | -2.45
| PreferenceStore.Save | p99 | 93ms | 91ms | -2ms | -2.15
| ChannelStore.CreateDirectChannel | p99 | 96ms | 94ms | -2ms | -2.09
| ProductNoticesStore.View | p99 | 238ms | 234ms | -4ms | -1.68
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | avg | 58ms | 86ms | 28ms | 48.47
| patchPost | avg | 28ms | 37ms | 9ms | 32.05
| createDirectChannel | avg | 309ms | 338ms | 29ms | 9.37
| createGroupChannel | avg | 449ms | 491ms | 42ms | 9.35
| getTeamStats | avg | 64ms | 69ms | 5ms | 7.86
| autocompleteChannelsForTeamForSearch | avg | 79ms | 84ms | 5ms | 6.36
| createPost | avg | 336ms | 352ms | 16ms | 4.76
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 99ms | 478ms | 379ms | 382.83
| getTeamMember | p99 | 24ms | 36ms | 12ms | 50.96
| removeUserCustomStatus | p99 | 487ms | 700ms | 213ms | 43.75
| autocompleteChannelsForTeamForSearch | p99 | 2.725s | 3.567s | 842ms | 30.90
| getPostThread | p99 | 69ms | 83ms | 14ms | 20.25
| getChannelStats | p99 | 53ms | 59ms | 6ms | 11.33
| getUser | p99 | 66ms | 73ms | 7ms | 10.63
| updatePreferences | p99 | 38ms | 41ms | 3ms | 7.90
| saveReaction | p99 | 81ms | 86ms | 5ms | 6.15
| addTeamMember | p99 | 3.384s | 3.58s | 196ms | 5.79
| getCategoriesForTeamForUser | p99 | 164ms | 173ms | 9ms | 5.47
| addChannelMember | p99 | 760ms | 797ms | 37ms | 4.87
| getTeamsForUser | p99 | 41ms | 43ms | 2ms | 4.85
| getChannelsForTeamForUser | p99 | 41ms | 43ms | 2ms | 4.84
| getChannelUnread | p99 | 44ms | 46ms | 2ms | 4.57
| getUsers | p99 | 67ms | 70ms | 3ms | 4.46
| getProfileImage | p99 | 399ms | 414ms | 15ms | 3.76
| getTeamStats | p99 | 237ms | 243ms | 6ms | 2.54
| getPostsForChannelAroundLastUnread | p99 | 218ms | 223ms | 5ms | 2.29
| viewChannel | p99 | 89ms | 91ms | 2ms | 2.26
| getFileThumbnail | p99 | 94ms | 96ms | 2ms | 2.12
| createDirectChannel | p99 | 894ms | 903ms | 9ms | 1.01
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 36ms | 0s | -36ms | -100.16
| createChannel | avg | 296ms | 246ms | -50ms | -16.92
| updateReadStateThreadByUser | avg | 42ms | 37ms | -5ms | -11.85
| updateCategoriesForTeamForUser | avg | 132ms | 121ms | -11ms | -8.33
| removeUserCustomStatus | avg | 194ms | 183ms | -11ms | -5.67
| addChannelMember | avg | 281ms | 267ms | -14ms | -4.99
| autocompleteUsers | avg | 44ms | 42ms | -2ms | -4.57
| searchPostsInTeam | avg | 174ms | 170ms | -4ms | -2.30
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| getChannel | p99 | 68ms | 25ms | -43ms | -63.00
| updateCategoriesForTeamForUser | p99 | 920ms | 462ms | -458ms | -49.78
| patchPost | p99 | 174ms | 100ms | -74ms | -42.46
| getChannelMember | p99 | 129ms | 99ms | -30ms | -23.33
| getDrafts | p99 | 38ms | 33ms | -5ms | -13.17
| autocompleteUsers | p99 | 321ms | 285ms | -36ms | -11.23
| unfollowThreadByUser | p99 | 44ms | 40ms | -4ms | -9.18
| login | p99 | 664ms | 625ms | -39ms | -5.87
| updateReadStateThreadByUser | p99 | 199ms | 191ms | -8ms | -4.03
| getTeamMembersForUser | p99 | 52ms | 50ms | -2ms | -3.86
| createUser | p99 | 821ms | 812ms | -9ms | -1.10
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 38ms | 0s | 0.000
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| BotStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 27ms | -3ms | -10.101
| ChannelStore.Autocomplete |  Avg| 44ms| 45ms | 1ms | 2.250
| |  P99| 99ms| 100ms | 1ms | 1.007
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 78ms| 84ms | 6ms | 7.675
| |  P99| 2.725s| 3.567s | 842ms | 30.901
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 96ms| 94ms | -2ms | -2.091
| ChannelStore.CreateInitialSidebarCategories |  Avg| 41ms| 41ms | 0s | 0.000
| |  P99| 221ms| 222ms | 1ms | 0.452
| ChannelStore.CreateSidebarCategory |  Avg| 34ms| 0s | -34ms | -101.478
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 14ms| 13ms | -1ms | -7.104
| |  P99| 50ms| 45ms | -5ms | -10.079
| ChannelStore.GetAllChannelMembersForUser |  Avg| 6ms| 7ms | 1ms | 15.692
| |  P99| 33ms| 42ms | 9ms | 27.645
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 24ms| 27ms | 3ms | 12.649
| |  P99| 226ms| 280ms | 54ms | 23.868
| ChannelStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 43ms | -1ms | -2.286
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 12.069
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.706
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.315
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 28ms | 2ms | 7.833
| ChannelStore.GetGuestCount |  Avg| 4ms| 5ms | 1ms | 22.334
| |  P99| 43ms| 45ms | 2ms | 4.650
| ChannelStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 40ms | -5ms | -11.182
| ChannelStore.GetMemberCount |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 87ms| 90ms | 3ms | 3.432
| ChannelStore.GetMemberForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.007
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 4ms | 1ms | 30.213
| |  P99| 35ms| 39ms | 4ms | 11.435
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 29ms| 29ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 119.789
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.037
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 36ms| 37ms | 1ms | 2.777
| |  P99| 154ms| 164ms | 10ms | 6.486
| ChannelStore.GetSidebarCategory |  Avg| 19ms| 24ms | 5ms | 25.763
| |  P99| 202ms| 227ms | 25ms | 12.378
| ChannelStore.GetTeamChannels |  Avg| 22ms| 20ms | -2ms | -8.974
| |  P99| 96ms| 49ms | -47ms | -49.214
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.107
| ChannelStore.Save |  Avg| 10ms| 11ms | 1ms | 9.600
| |  P99| 63ms| 148ms | 85ms | 135.981
| ChannelStore.SaveMember |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 220ms| 222ms | 2ms | 0.909
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 46ms| 47ms | 1ms | 2.189
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 90ms| 69ms | -21ms | -23.432
| |  P99| 920ms| 227ms | -693ms | -75.329
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.080
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 4ms | -1ms | -21.468
| |  P99| 43ms| 56ms | 13ms | 29.887
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.729
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 5ms | 1ms | 22.646
| |  P99| 24ms| 23ms | -1ms | -4.202
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 31ms | -5ms | -14.003
| DraftStore.Upsert |  Avg| 3ms| 4ms | 1ms | 28.981
| |  P99| 25ms| 27ms | 2ms | 7.936
| EmojiStore.GetByName |  Avg| 2ms| 3ms | 1ms | 41.299
| |  P99| 23ms| 24ms | 1ms | 4.336
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 6ms | 1ms | 19.051
| |  P99| 23ms| 44ms | 21ms | 89.997
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 19ms | 4ms | 26.920
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.338
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.364
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 34ms | 10ms | 41.415
| FileInfoStore.SetContent |  Avg| 7ms| 8ms | 1ms | 14.620
| |  P99| 44ms| 49ms | 5ms | 11.250
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 33ms | 1ms | 3.096
| GroupStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 12.148
| JobStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 18ms | -20ms | -52.632
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 39ms | -4ms | -9.352
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 4ms | 2ms | 105.824
| |  P99| 5ms| 44ms | 39ms | 787.879
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 38ms | 12ms | 47.059
| JobStore.Save |  Avg| 3ms| 5ms | 2ms | 62.070
| |  P99| 18ms| 77ms | 59ms | 328.691
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -50.562
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -50.562
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -23.162
| |  P99| 38ms| 18ms | -20ms | -52.632
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.288
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PluginStore.List |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 41ms | 21ms | 107.129
| PluginStore.SetWithOptions |  Avg| 5ms| 4ms | -1ms | -19.651
| |  P99| 47ms| 40ms | -7ms | -15.011
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 33ms | 11ms | 49.497
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 4ms | 1ms | 28.879
| |  P99| 30ms| 32ms | 2ms | 6.736
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 1ms | -1ms | -49.242
| |  P99| 43ms| 9ms | -34ms | -79.532
| PostPersistentNotificationStore.Get |  Avg| 2ms| 1ms | -1ms | -42.334
| |  P99| 43ms| 21ms | -22ms | -51.462
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.234
| PostPriorityStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -28.471
| |  P99| 57ms| 29ms | -28ms | -49.339
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 34ms | 1ms | 3.021
| PostStore.AnalyticsPostCount |  Avg| 443ms| 443ms | 0s | 0.000
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.326
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 35ms | 2ms | 6.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 32ms | 2ms | 6.682
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 3ms | -1ms | -24.356
| |  P99| 23ms| 9ms | -14ms | -60.320
| PostStore.GetPostReminders |  Avg| 5ms| 3ms | -2ms | -37.591
| |  P99| 46ms| 9ms | -37ms | -80.874
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 39ms | 1ms | 2.639
| PostStore.GetPostsAfter |  Avg| 4ms| 3ms | -1ms | -27.828
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 28ms| 28ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 6ms| 4ms | -2ms | -33.527
| |  P99| 25ms| 22ms | -3ms | -12.199
| PostStore.GetPostsSince |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 77ms| 78ms | 1ms | 1.301
| PostStore.GetSingle |  Avg| 2ms| 3ms | 1ms | 40.634
| |  P99| 18ms| 20ms | 2ms | 10.930
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 82ms| 80ms | -2ms | -2.452
| PostStore.SearchPostsForUser |  Avg| 164ms| 160ms | -4ms | -2.433
| |  P99| 2.319s| 2.301s | -18ms | -0.776
| PostStore.SetPostReminder |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 11ms | -2ms | -15.922
| |  P99| 50ms| 25ms | -25ms | -50.081
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.202
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 44ms | 2ms | 4.706
| PreferenceStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 91ms | -2ms | -2.153
| ProductNoticesStore.ClearOldNotices |  Avg| 19ms| 18ms | -1ms | -5.288
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 238ms| 234ms | -4ms | -1.681
| ReactionStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 31.112
| |  P99| 19ms| 23ms | 4ms | 20.619
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 7ms | 1ms | 16.492
| |  P99| 24ms| 44ms | 20ms | 84.138
| RoleStore.GetByNames |  Avg| 0s| 11ms | 11ms | 3802035.679
| |  P99| 5ms| 48ms | 43ms | 868.685
| SessionStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 73ms| 77ms | 4ms | 5.511
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 33ms | 3ms | 9.970
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.040
| SessionStore.Remove |  Avg| 3ms| 7ms | 4ms | 158.457
| |  P99| 5ms| 48ms | 43ms | 868.687
| SessionStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 51ms| 50ms | -1ms | -1.977
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.713
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 34ms | -2ms | -5.549
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.991
| StatusStore.SaveOrUpdate |  Avg| 18ms| 17ms | -1ms | -5.600
| |  P99| 384ms| 361ms | -23ms | -5.996
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.710
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 32ms | 0s | 0.000
| SystemStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.897
| TeamStore.GetActiveMemberCount |  Avg| 60ms| 65ms | 5ms | 8.390
| |  P99| 237ms| 243ms | 6ms | 2.537
| TeamStore.GetAllPage |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 41ms | 2ms | 5.112
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 35ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.295
| TeamStore.GetTeamsByUserId |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.838
| TeamStore.GetTeamsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 39ms | 1ms | 2.627
| TeamStore.GetTotalMemberCount |  Avg| 50ms| 43ms | -7ms | -13.934
| |  P99| 99ms| 243ms | 144ms | 145.088
| TeamStore.SaveMember |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 155ms| 164ms | 9ms | 5.797
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.775
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.393
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 41ms| 44ms | 3ms | 7.235
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 7ms| 6ms | -1ms | -15.002
| |  P99| 41ms| 37ms | -4ms | -9.660
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 7ms| 5ms | -2ms | -29.926
| |  P99| 25ms| 24ms | -1ms | -4.027
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 28ms| 28ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 34ms | 2ms | 6.164
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.841
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 34ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 35ms | 1ms | 2.935
| ThreadStore.MaintainMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 3ms | 2ms | 138.645
| |  P99| 5ms| 43ms | 38ms | 767.677
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.564
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.379
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 48ms| 46ms | -2ms | -4.153
| |  P99| 363ms| 334ms | -29ms | -7.995
| UserStore.Count |  Avg| 15ms| 14ms | -1ms | -6.532
| |  P99| 48ms| 47ms | -1ms | -2.094
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.681
| UserStore.GetAllProfiles |  Avg| 5ms| 4ms | -1ms | -22.196
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 260ms| 263ms | 3ms | 1.155
| |  P99| 923ms| 931ms | 8ms | 0.867
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.887
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 40ms | 1ms | 2.584
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 30ms | -2ms | -6.217
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 17ms| 19ms | 2ms | 11.738
| |  P99| 48ms| 49ms | 1ms | 2.094
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 6ms | 1ms | 19.195
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 26ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.Save |  Avg| 74ms| 74ms | 0s | 0.000
| |  P99| 229ms| 231ms | 2ms | 0.872
| UserStore.Search |  Avg| 37ms| 38ms | 1ms | 2.685
| |  P99| 98ms| 99ms | 1ms | 1.017
| UserStore.Update |  Avg| 6ms| 7ms | 1ms | 16.646
| |  P99| 35ms| 85ms | 50ms | 141.154
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 39ms | 2ms | 5.415
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 26ms| 28ms | 2ms | 7.646
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 30ms| 33ms | 3ms | 9.951
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.895
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 41ms| 40ms | -1ms | -2.428
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 281ms| 267ms | -14ms | -4.989
| | P99| 760ms| 797ms | 37ms | 4.869
| addTeamMember | Avg| 950ms| 953ms | 3ms | 0.316
| | P99| 3.384s| 3.58s | 196ms | 5.793
| autocompleteChannelsForTeamForSearch | Avg| 79ms| 84ms | 5ms | 6.360
| | P99| 2.725s| 3.567s | 842ms | 30.901
| autocompleteUsers | Avg| 44ms| 42ms | -2ms | -4.566
| | P99| 321ms| 285ms | -36ms | -11.232
| createCategoryForTeamForUser | Avg| 36ms| 0s | -36ms | -100.159
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 296ms| 246ms | -50ms | -16.917
| | P99| 497ms| 496ms | -1ms | -0.201
| createDirectChannel | Avg| 309ms| 338ms | 29ms | 9.372
| | P99| 894ms| 903ms | 9ms | 1.007
| createGroupChannel | Avg| 449ms| 491ms | 42ms | 9.351
| | P99| 985ms| 991ms | 6ms | 0.609
| createPost | Avg| 336ms| 352ms | 16ms | 4.763
| | P99| 2.056s| 2.047s | -9ms | -0.438
| createUser | Avg| 170ms| 171ms | 1ms | 0.587
| | P99| 821ms| 812ms | -9ms | -1.096
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.659
| deletePost | Avg| 14ms| 15ms | 1ms | 7.095
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 12ms | 1ms | 9.380
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 4ms| 5ms | 1ms | 22.273
| | P99| 47ms| 47ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 36ms| 37ms | 1ms | 2.745
| | P99| 164ms| 173ms | 9ms | 5.474
| getChannel | Avg| 9ms| 8ms | -1ms | -10.905
| | P99| 68ms| 25ms | -43ms | -62.996
| getChannelMember | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 129ms| 99ms | -30ms | -23.334
| getChannelMembers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 39ms| 39ms | 0s | 0.000
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 53ms| 59ms | 6ms | 11.328
| getChannelUnread | Avg| 4ms| 5ms | 1ms | 22.998
| | P99| 44ms| 46ms | 2ms | 4.572
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 41ms| 43ms | 2ms | 4.839
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.706
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 93ms| 92ms | -1ms | -1.081
| getDrafts | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 38ms| 33ms | -5ms | -13.166
| getFilePreview | Avg| 43ms| 44ms | 1ms | 2.302
| | P99| 193ms| 193ms | 0s | 0.000
| getFileThumbnail | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 94ms| 96ms | 2ms | 2.122
| getPostThread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 69ms| 83ms | 14ms | 20.251
| getPostsForChannel | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 230ms| 231ms | 1ms | 0.435
| getPostsForChannelAroundLastUnread | Avg| 24ms| 25ms | 1ms | 4.089
| | P99| 218ms| 223ms | 5ms | 2.291
| getPreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 46ms| 47ms | 1ms | 2.197
| getProfileImage | Avg| 81ms| 81ms | 0s | 0.000
| | P99| 399ms| 414ms | 15ms | 3.756
| getPublicChannelsForTeam | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 49ms| 50ms | 1ms | 2.029
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 36ms | 12ms | 50.955
| getTeamMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 52ms| 50ms | -2ms | -3.858
| getTeamStats | Avg| 64ms| 69ms | 5ms | 7.860
| | P99| 237ms| 243ms | 6ms | 2.537
| getTeamsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 41ms| 43ms | 2ms | 4.854
| getTeamsUnreadForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 65ms| 65ms | 0s | 0.000
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 39ms| 40ms | 1ms | 2.547
| getUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 66ms| 73ms | 7ms | 10.632
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 7ms | 1ms | 15.446
| | P99| 67ms| 70ms | 3ms | 4.462
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.139
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 94ms| 93ms | -1ms | -1.069
| | P99| 664ms| 625ms | -39ms | -5.874
| logout | Avg| 58ms| 86ms | 28ms | 48.467
| | P99| 99ms| 478ms | 379ms | 382.828
| patchPost | Avg| 28ms| 37ms | 9ms | 32.052
| | P99| 174ms| 100ms | -74ms | -42.463
| removeUserCustomStatus | Avg| 194ms| 183ms | -11ms | -5.672
| | P99| 487ms| 700ms | 213ms | 43.754
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 81ms| 86ms | 5ms | 6.149
| searchAllChannels | Avg| 45ms| 45ms | 0s | 0.000
| | P99| 99ms| 100ms | 1ms | 1.007
| searchGroupChannels | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 46ms| 47ms | 1ms | 2.176
| searchPostsInTeam | Avg| 174ms| 170ms | -4ms | -2.301
| | P99| 2.351s| 2.343s | -8ms | -0.340
| searchUsers | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| setPostReminder | Avg| 17ms| 16ms | -1ms | -5.796
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 44ms| 40ms | -4ms | -9.183
| updateCategoriesForTeamForUser | Avg| 132ms| 121ms | -11ms | -8.326
| | P99| 920ms| 462ms | -458ms | -49.785
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 38ms| 41ms | 3ms | 7.903
| updateReadStateThreadByUser | Avg| 42ms| 37ms | -5ms | -11.847
| | P99| 199ms| 191ms | -8ms | -4.028
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 382ms| 384ms | 2ms | 0.523
| | P99| 986ms| 990ms | 4ms | 0.406
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 36ms| 37ms | 1ms | 2.768
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 89ms| 91ms | 2ms | 2.257
