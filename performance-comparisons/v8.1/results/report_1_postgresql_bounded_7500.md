### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 53ms | 60ms | 7ms | 13.10
| ChannelStore.CreateSidebarCategory | avg | 39ms | 42ms | 3ms | 7.67
| UserStore.AutocompleteUsersInChannel | avg | 56ms | 59ms | 3ms | 5.39
| ChannelStore.UpdateSidebarCategories | avg | 67ms | 70ms | 3ms | 4.50
| UserStore.GetAllProfilesInChannel | avg | 204ms | 209ms | 5ms | 2.45
| UserStore.InvalidateProfilesInChannelCacheByUser | avg | 121ms | 123ms | 2ms | 1.66
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.List | p99 | 8ms | 41ms | 33ms | 402.44
| PostStore.GetPostReminders | p99 | 9ms | 22ms | 13ms | 142.08
| UserAccessTokenStore.GetByToken | p99 | 23ms | 41ms | 18ms | 78.02
| ThreadStore.MarkAllAsReadByTeam | p99 | 27ms | 45ms | 18ms | 66.99
| ChannelStore.UpdateSidebarCategories | p99 | 236ms | 390ms | 154ms | 65.27
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.183s | 1.786s | 603ms | 50.97
| UserStore.Update | p99 | 52ms | 78ms | 26ms | 49.54
| ChannelStore.GetSidebarCategory | p99 | 58ms | 86ms | 28ms | 48.00
| ClusterDiscoveryStore.SetLastPingAt | p99 | 24ms | 35ms | 11ms | 45.64
| UserStore.GetMany | p99 | 16ms | 22ms | 6ms | 37.59
| ThreadStore.MarkAllAsReadByChannels | p99 | 22ms | 30ms | 8ms | 36.02
| SessionStore.Remove | p99 | 22ms | 30ms | 8ms | 35.89
| ChannelStore.GetFileCount | p99 | 23ms | 30ms | 7ms | 30.09
| UserStore.GetUnreadCount | p99 | 27ms | 35ms | 8ms | 29.26
| JobStore.GetAllByStatus | p99 | 34ms | 43ms | 9ms | 26.64
| TeamStore.SaveMember | p99 | 104ms | 129ms | 25ms | 24.01
| PostStore.Delete | p99 | 59ms | 73ms | 14ms | 23.93
| FileInfoStore.AttachToPost | p99 | 38ms | 45ms | 7ms | 18.61
| PostStore.GetPostIdAfterTime | p99 | 27ms | 32ms | 5ms | 18.22
| TeamStore.GetMember | p99 | 28ms | 33ms | 5ms | 18.13
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 127ms | 150ms | 23ms | 18.10
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 99ms | 116ms | 17ms | 17.12
| ChannelStore.CreateSidebarCategory | p99 | 191ms | 220ms | 29ms | 15.17
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 20ms | 23ms | 3ms | 14.77
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 27ms | 31ms | 4ms | 14.72
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 29ms | 33ms | 4ms | 13.76
| SessionStore.Save | p99 | 71ms | 80ms | 9ms | 12.74
| TeamStore.Get | p99 | 25ms | 28ms | 3ms | 12.04
| ChannelStore.GetChannels | p99 | 34ms | 38ms | 4ms | 11.74
| GroupStore.GetGroups | p99 | 17ms | 19ms | 2ms | 11.66
| PostStore.GetPosts | p99 | 35ms | 39ms | 4ms | 11.40
| FileInfoStore.Get | p99 | 21ms | 23ms | 2ms | 9.65
| PostPriorityStore.GetForPost | p99 | 22ms | 24ms | 2ms | 9.29
| ChannelStore.GetChannelUnread | p99 | 23ms | 25ms | 2ms | 8.85
| ThreadStore.GetTotalUnreadThreads | p99 | 35ms | 38ms | 3ms | 8.62
| ThreadStore.GetTotalThreads | p99 | 35ms | 38ms | 3ms | 8.56
| SystemStore.GetByName | p99 | 36ms | 39ms | 3ms | 8.38
| ChannelStore.GetMembersForUser | p99 | 36ms | 39ms | 3ms | 8.22
| PostAcknowledgementStore.GetForPosts | p99 | 25ms | 27ms | 2ms | 8.06
| PostPriorityStore.GetForPosts | p99 | 25ms | 27ms | 2ms | 8.06
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 37ms | 40ms | 3ms | 8.05
| ThreadStore.GetThreadsForUser | p99 | 37ms | 40ms | 3ms | 8.02
| UserStore.UpdateUpdateAt | p99 | 38ms | 41ms | 3ms | 7.84
| TeamStore.GetTeamsByUserId | p99 | 39ms | 42ms | 3ms | 7.68
| PluginStore.Delete | p99 | 28ms | 30ms | 2ms | 7.15
| PostStore.Get | p99 | 42ms | 45ms | 3ms | 7.10
| WebhookStore.GetOutgoingByTeam | p99 | 44ms | 47ms | 3ms | 6.77
| ChannelStore.CreateDirectChannel | p99 | 153ms | 162ms | 9ms | 5.87
| ThreadStore.GetTotalUnreadMentions | p99 | 37ms | 39ms | 2ms | 5.45
| UserTermsOfServiceStore.GetByUser | p99 | 38ms | 40ms | 2ms | 5.27
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 39ms | 41ms | 2ms | 5.18
| PreferenceStore.DeleteCategoryAndName | p99 | 58ms | 61ms | 3ms | 5.13
| ChannelStore.SaveMember | p99 | 198ms | 208ms | 10ms | 5.05
| ThreadStore.GetThreadForUser | p99 | 41ms | 43ms | 2ms | 4.93
| TeamStore.GetAllPage | p99 | 41ms | 43ms | 2ms | 4.88
| TeamStore.GetTeamsForUser | p99 | 41ms | 43ms | 2ms | 4.87
| AuditStore.Save | p99 | 41ms | 43ms | 2ms | 4.87
| PostStore.Save | p99 | 83ms | 87ms | 4ms | 4.84
| PreferenceStore.Save | p99 | 85ms | 89ms | 4ms | 4.70
| ReactionStore.Save | p99 | 85ms | 89ms | 4ms | 4.68
| ThreadStore.MaintainMembership | p99 | 44ms | 46ms | 2ms | 4.58
| ChannelStore.GetByName | p99 | 45ms | 47ms | 2ms | 4.42
| ThreadStore.GetTeamsUnreadForUser | p99 | 46ms | 48ms | 2ms | 4.30
| ChannelStore.GetMemberCount | p99 | 47ms | 49ms | 2ms | 4.24
| UserStore.AutocompleteUsersInChannel | p99 | 429ms | 439ms | 10ms | 2.33
| PostStore.GetPostsSince | p99 | 89ms | 91ms | 2ms | 2.24
| UserStore.InvalidateProfilesInChannelCacheByUser | p99 | 469ms | 474ms | 5ms | 1.07
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | avg | 6ms | 0s | -6ms | -101.07
| PostStore.SetPostReminder | avg | 15ms | 6ms | -9ms | -61.71
| StatusStore.SaveOrUpdate | avg | 51ms | 22ms | -29ms | -57.38
| StatusStore.UpdateExpiredDNDStatuses | avg | 4ms | 2ms | -2ms | -57.03
| PostStore.GetPostReminderMetadata | avg | 6ms | 3ms | -3ms | -47.14
| PostStore.SearchPostsForUser | avg | 153ms | 145ms | -8ms | -5.24
| UserStore.Count | avg | 50ms | 48ms | -2ms | -4.02
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.InvalidateFileInfosForPostCache | p99 | 5ms | 0s | -5ms | -101.01
| FileInfoStore.DeleteForPost | p99 | 10ms | 0s | -10ms | -100.60
| PostStore.GetPostReminderMetadata | p99 | 184ms | 18ms | -166ms | -90.23
| PostStore.SetPostReminder | p99 | 214ms | 44ms | -170ms | -79.44
| JobStore.GetNewestJobByStatusesAndType | p99 | 20ms | 9ms | -11ms | -56.12
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 22ms | -24ms | -52.46
| StatusStore.SaveOrUpdate | p99 | 817ms | 446ms | -371ms | -45.43
| JobStore.GetCountByStatusAndType | p99 | 9ms | 5ms | -4ms | -43.96
| JobStore.Save | p99 | 9ms | 5ms | -4ms | -43.72
| JobStore.Get | p99 | 9ms | 5ms | -4ms | -43.24
| UserStore.GetByUsername | p99 | 33ms | 20ms | -13ms | -40.00
| ChannelStore.Save | p99 | 131ms | 92ms | -39ms | -29.74
| FileInfoStore.Save | p99 | 46ms | 35ms | -11ms | -23.96
| LinkMetadataStore.Save | p99 | 21ms | 17ms | -4ms | -19.41
| LinkMetadataStore.Get | p99 | 16ms | 13ms | -3ms | -18.87
| ChannelStore.GetTeamChannels | p99 | 95ms | 80ms | -15ms | -15.78
| PluginStore.SetWithOptions | p99 | 58ms | 50ms | -8ms | -13.85
| PostAcknowledgementStore.GetForPost | p99 | 26ms | 24ms | -2ms | -7.67
| TeamStore.GetByName | p99 | 26ms | 24ms | -2ms | -7.62
| ChannelStore.GetMembers | p99 | 242ms | 231ms | -11ms | -4.54
| PostStore.SearchPostsForUser | p99 | 2.25s | 2.179s | -71ms | -3.16
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 53ms | 60ms | 7ms | 13.09
| deletePost | avg | 20ms | 22ms | 2ms | 10.20
| createCategoryForTeamForUser | avg | 42ms | 46ms | 4ms | 9.45
| updateCategoriesForTeamForUser | avg | 101ms | 107ms | 6ms | 5.91
| logout | avg | 54ms | 57ms | 3ms | 5.52
| updateReadStateThreadByUser | avg | 41ms | 43ms | 2ms | 4.91
| createPost | avg | 391ms | 408ms | 17ms | 4.34
| createGroupChannel | avg | 430ms | 442ms | 12ms | 2.79
| createUser | avg | 111ms | 114ms | 3ms | 2.69
| getPostsForChannel | avg | 75ms | 77ms | 2ms | 2.66
| addTeamMember | avg | 1.074s | 1.101s | 27ms | 2.51
| removeUserCustomStatus | avg | 172ms | 176ms | 4ms | 2.32
| addChannelMember | avg | 233ms | 238ms | 5ms | 2.15
| createDirectChannel | avg | 274ms | 279ms | 5ms | 1.83
| login | avg | 125ms | 127ms | 2ms | 1.61
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | p99 | 67ms | 173ms | 106ms | 158.20
| updateCategoriesForTeamForUser | p99 | 312ms | 530ms | 218ms | 69.76
| updateReadStateAllThreadsByUser | p99 | 27ms | 45ms | 18ms | 66.99
| autocompleteChannelsForTeamForSearch | p99 | 1.183s | 1.786s | 603ms | 50.97
| getChannelUnread | p99 | 28ms | 38ms | 10ms | 35.92
| unfollowThreadByUser | p99 | 68ms | 81ms | 13ms | 18.98
| createCategoryForTeamForUser | p99 | 201ms | 232ms | 31ms | 15.46
| getCategoriesForTeamForUser | p99 | 141ms | 160ms | 19ms | 13.44
| getPostThread | p99 | 99ms | 111ms | 12ms | 12.18
| getTeamsUnreadForUser | p99 | 67ms | 74ms | 7ms | 10.45
| getUsers | p99 | 79ms | 87ms | 8ms | 10.11
| getChannel | p99 | 53ms | 58ms | 5ms | 9.45
| login | p99 | 717ms | 784ms | 67ms | 9.35
| viewChannel | p99 | 161ms | 175ms | 14ms | 8.71
| createGroupChannel | p99 | 1.699s | 1.821s | 122ms | 7.18
| createPost | p99 | 1.88s | 2.005s | 125ms | 6.65
| getChannelsForTeamForUser | p99 | 46ms | 49ms | 3ms | 6.51
| getUsersByNames | p99 | 32ms | 34ms | 2ms | 6.25
| getChannelStats | p99 | 89ms | 94ms | 5ms | 5.65
| getUser | p99 | 77ms | 81ms | 4ms | 5.22
| addTeamMember | p99 | 4.038s | 4.244s | 206ms | 5.10
| getTeamsForUser | p99 | 40ms | 42ms | 2ms | 5.06
| getThreadsForUser | p99 | 40ms | 42ms | 2ms | 4.97
| getChannelMembers | p99 | 44ms | 46ms | 2ms | 4.54
| getChannelMembersForTeamForUser | p99 | 44ms | 46ms | 2ms | 4.50
| updateReadStateThreadByUser | p99 | 204ms | 213ms | 9ms | 4.42
| getClientConfig | p99 | 92ms | 96ms | 4ms | 4.33
| getAllTeams | p99 | 47ms | 49ms | 2ms | 4.30
| getTeamMembersForUser | p99 | 48ms | 50ms | 2ms | 4.18
| autocompleteUsers | p99 | 364ms | 378ms | 14ms | 3.84
| createUser | p99 | 434ms | 447ms | 13ms | 3.00
| getPostsForChannelAroundLastUnread | p99 | 217ms | 223ms | 6ms | 2.77
| addChannelMember | p99 | 867ms | 887ms | 20ms | 2.31
| logout | p99 | 232ms | 237ms | 5ms | 2.15
| getPostsForChannel | p99 | 883ms | 893ms | 10ms | 1.13
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 108ms | 39ms | -69ms | -63.66
| setPostReminder | avg | 40ms | 22ms | -18ms | -44.89
| getProfileImage | avg | 122ms | 102ms | -20ms | -16.42
| searchPostsInTeam | avg | 168ms | 159ms | -9ms | -5.34
| getFilePreview | avg | 43ms | 41ms | -2ms | -4.63
| uploadFileStream | avg | 454ms | 442ms | -12ms | -2.64
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 440ms | 49ms | -391ms | -88.87
| patchPost | p99 | 605ms | 234ms | -371ms | -61.36
| getTopThreadsForUserSince | p99 | 40ms | 20ms | -20ms | -50.10
| updateUserCustomStatus | p99 | 623ms | 500ms | -123ms | -19.76
| getFileThumbnail | p99 | 126ms | 108ms | -18ms | -14.28
| createChannel | p99 | 95ms | 82ms | -13ms | -13.68
| getFilePreview | p99 | 208ms | 193ms | -15ms | -7.22
| getProfileImage | p99 | 478ms | 454ms | -24ms | -5.02
| followThreadByUser | p99 | 100ms | 95ms | -5ms | -5.02
| updatePreferences | p99 | 73ms | 70ms | -3ms | -4.13
| saveReaction | p99 | 202ms | 197ms | -5ms | -2.48
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.865
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| BotStore.Save |  Avg| 3ms| 2ms | -1ms | -39.355
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 31ms | 4ms | 14.722
| ChannelStore.Autocomplete |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 53ms| 60ms | 7ms | 13.102
| |  P99| 1.183s| 1.786s | 603ms | 50.967
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 153ms| 162ms | 9ms | 5.866
| ChannelStore.CreateInitialSidebarCategories |  Avg| 46ms| 47ms | 1ms | 2.192
| |  P99| 242ms| 240ms | -2ms | -0.828
| ChannelStore.CreateSidebarCategory |  Avg| 39ms| 42ms | 3ms | 7.669
| |  P99| 191ms| 220ms | 29ms | 15.166
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.494
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 99ms| 116ms | 17ms | 17.125
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.416
| ChannelStore.GetChannelUnread |  Avg| 2ms| 3ms | 1ms | 42.937
| |  P99| 23ms| 25ms | 2ms | 8.849
| ChannelStore.GetChannels |  Avg| 3ms| 4ms | 1ms | 29.344
| |  P99| 34ms| 38ms | 4ms | 11.735
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 30ms | 7ms | 30.086
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.582
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.599
| ChannelStore.GetMemberCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 49ms | 2ms | 4.236
| ChannelStore.GetMemberForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 242ms| 231ms | -11ms | -4.543
| ChannelStore.GetMembersForUser |  Avg| 4ms| 5ms | 1ms | 23.146
| |  P99| 36ms| 39ms | 3ms | 8.225
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.505
| ChannelStore.GetPublicChannelsForTeam |  Avg| 17ms| 18ms | 1ms | 5.786
| |  P99| 56ms| 56ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 33ms| 34ms | 1ms | 3.073
| |  P99| 127ms| 150ms | 23ms | 18.101
| ChannelStore.GetSidebarCategory |  Avg| 16ms| 17ms | 1ms | 6.261
| |  P99| 58ms| 86ms | 28ms | 48.001
| ChannelStore.GetTeamChannels |  Avg| 21ms| 20ms | -1ms | -4.844
| |  P99| 95ms| 80ms | -15ms | -15.783
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 31ms | -1ms | -3.104
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannel |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateMemberCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidatePinnedPostCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 131ms| 92ms | -39ms | -29.743
| ChannelStore.SaveMember |  Avg| 30ms| 31ms | 1ms | 3.328
| |  P99| 198ms| 208ms | 10ms | 5.048
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.152
| ChannelStore.UpdateSidebarCategories |  Avg| 67ms| 70ms | 3ms | 4.500
| |  P99| 236ms| 390ms | 154ms | 65.272
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 35ms | 11ms | 45.643
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.848
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 45ms | 7ms | 18.608
| FileInfoStore.DeleteForPost |  Avg| 6ms| 0s | -6ms | -101.071
| |  P99| 10ms| 0s | -10ms | -100.600
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.646
| FileInfoStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.InvalidateFileInfosForPostCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 35ms | -11ms | -23.963
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 33ms | 4ms | 13.759
| GroupStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.658
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.243
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 43ms | 9ms | 26.641
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.956
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 9ms | -11ms | -56.122
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| JobStore.UpdateOptimistically |  Avg| 2ms| 3ms | 1ms | 40.639
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.867
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 17ms | -4ms | -19.409
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 30ms | 2ms | 7.148
| PluginStore.List |  Avg| 2ms| 3ms | 1ms | 56.380
| |  P99| 8ms| 41ms | 33ms | 402.439
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 58ms| 50ms | -8ms | -13.845
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -39.835
| |  P99| 26ms| 24ms | -2ms | -7.671
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.059
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.469
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 9.289
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.059
| PostStore.AnalyticsPostCount |  Avg| 754ms| 749ms | -5ms | -0.663
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 12ms| 13ms | 1ms | 8.623
| |  P99| 59ms| 73ms | 14ms | 23.930
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 45ms | 3ms | 7.104
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.461
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 32ms | 5ms | 18.219
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 6ms| 3ms | -3ms | -47.138
| |  P99| 184ms| 18ms | -166ms | -90.228
| PostStore.GetPostReminders |  Avg| 4ms| 5ms | 1ms | 25.024
| |  P99| 9ms| 22ms | 13ms | 142.077
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 39ms | 4ms | 11.397
| PostStore.GetPostsAfter |  Avg| 3ms| 4ms | 1ms | 30.036
| |  P99| 20ms| 21ms | 1ms | 4.914
| PostStore.GetPostsBefore |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 36ms| 37ms | 1ms | 2.779
| PostStore.GetPostsByThread |  Avg| 5ms| 6ms | 1ms | 18.485
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 89ms| 91ms | 2ms | 2.242
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 12ms | 1ms | 8.960
| |  P99| 83ms| 87ms | 4ms | 4.840
| PostStore.SearchPostsForUser |  Avg| 153ms| 145ms | -8ms | -5.241
| |  P99| 2.25s| 2.179s | -71ms | -3.156
| PostStore.SetPostReminder |  Avg| 15ms| 6ms | -9ms | -61.705
| |  P99| 214ms| 44ms | -170ms | -79.442
| PostStore.Update |  Avg| 13ms| 12ms | -1ms | -7.799
| |  P99| 48ms| 47ms | -1ms | -2.069
| PreferenceStore.DeleteCategoryAndName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 58ms| 61ms | 3ms | 5.128
| PreferenceStore.Get |  Avg| 2ms| 3ms | 1ms | 41.307
| |  P99| 24ms| 25ms | 1ms | 4.160
| PreferenceStore.GetAll |  Avg| 4ms| 5ms | 1ms | 23.115
| |  P99| 44ms| 45ms | 1ms | 2.266
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 89ms | 4ms | 4.703
| ProductNoticesStore.ClearOldNotices |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 30ms| 31ms | 1ms | 3.356
| |  P99| 237ms| 236ms | -1ms | -0.421
| ReactionStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 85ms| 89ms | 4ms | 4.681
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 83ms | -1ms | -1.194
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 23ms | 3ms | 14.775
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 30ms | 8ms | 35.891
| SessionStore.Save |  Avg| 8ms| 9ms | 1ms | 12.189
| |  P99| 71ms| 80ms | 9ms | 12.738
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| StatusStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.426
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.013
| StatusStore.SaveOrUpdate |  Avg| 51ms| 22ms | -29ms | -57.381
| |  P99| 817ms| 446ms | -371ms | -45.431
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 2ms | -2ms | -57.028
| |  P99| 46ms| 22ms | -24ms | -52.459
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.261
| SystemStore.GetByName |  Avg| 2ms| 3ms | 1ms | 41.964
| |  P99| 36ms| 39ms | 3ms | 8.385
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 42ms| 43ms | 1ms | 2.369
| TeamStore.Get |  Avg| 2ms| 3ms | 1ms | 40.435
| |  P99| 25ms| 28ms | 3ms | 12.038
| TeamStore.GetAllPage |  Avg| 3ms| 4ms | 1ms | 28.790
| |  P99| 41ms| 43ms | 2ms | 4.884
| TeamStore.GetByName |  Avg| 2ms| 3ms | 1ms | 42.160
| |  P99| 26ms| 24ms | -2ms | -7.619
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 41ms | 2ms | 5.185
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 33ms | 5ms | 18.126
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 4ms | 1ms | 29.505
| |  P99| 39ms| 42ms | 3ms | 7.679
| TeamStore.GetTeamsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.870
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 28ms| 29ms | 1ms | 3.540
| |  P99| 104ms| 129ms | 25ms | 24.013
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.830
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.005
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 48ms | 2ms | 4.305
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 3ms | 1ms | 40.253
| |  P99| 24ms| 25ms | 1ms | 4.113
| ThreadStore.GetThreadForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.934
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 40ms | 3ms | 8.023
| ThreadStore.GetTotalThreads |  Avg| 3ms| 4ms | 1ms | 29.528
| |  P99| 35ms| 38ms | 3ms | 8.557
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 4ms | 1ms | 28.815
| |  P99| 37ms| 39ms | 2ms | 5.453
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 4ms | 1ms | 29.207
| |  P99| 35ms| 38ms | 3ms | 8.615
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 40ms | 3ms | 8.047
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 46ms | 2ms | 4.584
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 3ms | 1ms | 43.162
| |  P99| 22ms| 30ms | 8ms | 36.025
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 45ms | 18ms | 66.987
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.951
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 41ms | 18ms | 78.019
| UserStore.AutocompleteUsersInChannel |  Avg| 56ms| 59ms | 3ms | 5.385
| |  P99| 429ms| 439ms | 10ms | 2.331
| UserStore.Count |  Avg| 50ms| 48ms | -2ms | -4.022
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 4ms| 5ms | 1ms | 23.181
| |  P99| 31ms| 32ms | 1ms | 3.253
| UserStore.GetAllProfilesInChannel |  Avg| 204ms| 209ms | 5ms | 2.449
| |  P99| 958ms| 961ms | 3ms | 0.313
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 20ms | -13ms | -40.000
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 22ms | 6ms | 37.593
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.024
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 32ms | 1ms | 3.259
| UserStore.GetProfilesInChannel |  Avg| 23ms| 24ms | 1ms | 4.310
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 35ms | 8ms | 29.264
| UserStore.GetUnreadCountForChannel |  Avg| 2ms| 3ms | 1ms | 41.163
| |  P99| 24ms| 25ms | 1ms | 4.191
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 121ms| 123ms | 2ms | 1.655
| |  P99| 469ms| 474ms | 5ms | 1.065
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.367
| UserStore.Save |  Avg| 75ms| 76ms | 1ms | 1.337
| |  P99| 235ms| 237ms | 2ms | 0.852
| UserStore.Search |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 8ms | 1ms | 13.649
| |  P99| 52ms| 78ms | 26ms | 49.537
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.319
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.844
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 40ms | 2ms | 5.270
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 47ms | 3ms | 6.771
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 233ms| 238ms | 5ms | 2.149
| | P99| 867ms| 887ms | 20ms | 2.308
| addTeamMember | Avg| 1.074s| 1.101s | 27ms | 2.514
| | P99| 4.038s| 4.244s | 206ms | 5.101
| autocompleteChannelsForTeamForSearch | Avg| 53ms| 60ms | 7ms | 13.086
| | P99| 1.183s| 1.786s | 603ms | 50.967
| autocompleteUsers | Avg| 37ms| 38ms | 1ms | 2.684
| | P99| 364ms| 378ms | 14ms | 3.843
| createCategoryForTeamForUser | Avg| 42ms| 46ms | 4ms | 9.445
| | P99| 201ms| 232ms | 31ms | 15.461
| createChannel | Avg| 21ms| 20ms | -1ms | -4.813
| | P99| 95ms| 82ms | -13ms | -13.679
| createDirectChannel | Avg| 274ms| 279ms | 5ms | 1.825
| | P99| 926ms| 924ms | -2ms | -0.216
| createGroupChannel | Avg| 430ms| 442ms | 12ms | 2.788
| | P99| 1.699s| 1.821s | 122ms | 7.181
| createPost | Avg| 391ms| 408ms | 17ms | 4.344
| | P99| 1.88s| 2.005s | 125ms | 6.649
| createUser | Avg| 111ms| 114ms | 3ms | 2.693
| | P99| 434ms| 447ms | 13ms | 2.996
| deletePost | Avg| 20ms| 22ms | 2ms | 10.203
| | P99| 67ms| 173ms | 106ms | 158.196
| followThreadByUser | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 100ms| 95ms | -5ms | -5.020
| getAllTeams | Avg| 4ms| 5ms | 1ms | 23.895
| | P99| 47ms| 49ms | 2ms | 4.295
| getCategoriesForTeamForUser | Avg| 33ms| 34ms | 1ms | 3.052
| | P99| 141ms| 160ms | 19ms | 13.438
| getChannel | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 53ms| 58ms | 5ms | 9.451
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 48ms| 47ms | -1ms | -2.100
| getChannelMembers | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 44ms| 46ms | 2ms | 4.543
| getChannelMembersForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 44ms| 46ms | 2ms | 4.505
| getChannelStats | Avg| 9ms| 10ms | 1ms | 10.596
| | P99| 89ms| 94ms | 5ms | 5.645
| getChannelUnread | Avg| 3ms| 4ms | 1ms | 28.690
| | P99| 28ms| 38ms | 10ms | 35.924
| getChannelsForTeamForUser | Avg| 4ms| 5ms | 1ms | 22.851
| | P99| 46ms| 49ms | 3ms | 6.515
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 92ms| 96ms | 4ms | 4.335
| getFilePreview | Avg| 43ms| 41ms | -2ms | -4.632
| | P99| 208ms| 193ms | -15ms | -7.221
| getFileThumbnail | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 126ms| 108ms | -18ms | -14.279
| getPostThread | Avg| 14ms| 15ms | 1ms | 7.174
| | P99| 99ms| 111ms | 12ms | 12.180
| getPostsForChannel | Avg| 75ms| 77ms | 2ms | 2.658
| | P99| 883ms| 893ms | 10ms | 1.132
| getPostsForChannelAroundLastUnread | Avg| 27ms| 28ms | 1ms | 3.700
| | P99| 217ms| 223ms | 6ms | 2.767
| getPreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 46ms| 46ms | 0s | 0.000
| getProfileImage | Avg| 122ms| 102ms | -20ms | -16.418
| | P99| 478ms| 454ms | -24ms | -5.024
| getPublicChannelsForTeam | Avg| 19ms| 20ms | 1ms | 5.352
| | P99| 64ms| 64ms | 0s | 0.000
| getTeamMembersForUser | Avg| 4ms| 5ms | 1ms | 23.161
| | P99| 48ms| 50ms | 2ms | 4.175
| getTeamsForUser | Avg| 3ms| 4ms | 1ms | 28.880
| | P99| 40ms| 42ms | 2ms | 5.058
| getTeamsUnreadForUser | Avg| 6ms| 7ms | 1ms | 15.398
| | P99| 67ms| 74ms | 7ms | 10.452
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 40ms| 42ms | 2ms | 4.974
| getTopThreadsForTeamSince | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTopThreadsForUserSince | Avg| 3ms| 2ms | -1ms | -31.818
| | P99| 40ms| 20ms | -20ms | -50.105
| getUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 77ms| 81ms | 4ms | 5.223
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 79ms| 87ms | 8ms | 10.110
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 12ms| 12ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 32ms| 34ms | 2ms | 6.251
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 125ms| 127ms | 2ms | 1.605
| | P99| 717ms| 784ms | 67ms | 9.348
| logout | Avg| 54ms| 57ms | 3ms | 5.524
| | P99| 232ms| 237ms | 5ms | 2.155
| patchPost | Avg| 108ms| 39ms | -69ms | -63.662
| | P99| 605ms| 234ms | -371ms | -61.356
| removeUserCustomStatus | Avg| 172ms| 176ms | 4ms | 2.322
| | P99| 495ms| 497ms | 2ms | 0.404
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 202ms| 197ms | -5ms | -2.479
| searchAllChannels | Avg| 42ms| 43ms | 1ms | 2.384
| | P99| 100ms| 100ms | 0s | 0.000
| searchGroupChannels | Avg| 14ms| 15ms | 1ms | 7.264
| | P99| 49ms| 48ms | -1ms | -2.047
| searchPostsInTeam | Avg| 168ms| 159ms | -9ms | -5.344
| | P99| 2.322s| 2.309s | -13ms | -0.560
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| setPostReminder | Avg| 40ms| 22ms | -18ms | -44.887
| | P99| 440ms| 49ms | -391ms | -88.866
| unfollowThreadByUser | Avg| 13ms| 14ms | 1ms | 7.430
| | P99| 68ms| 81ms | 13ms | 18.980
| updateCategoriesForTeamForUser | Avg| 101ms| 107ms | 6ms | 5.912
| | P99| 312ms| 530ms | 218ms | 69.763
| updatePreferences | Avg| 8ms| 7ms | -1ms | -13.259
| | P99| 73ms| 70ms | -3ms | -4.135
| updateReadStateAllThreadsByUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 27ms| 45ms | 18ms | 66.987
| updateReadStateThreadByUser | Avg| 41ms| 43ms | 2ms | 4.909
| | P99| 204ms| 213ms | 9ms | 4.420
| updateUserCustomStatus | Avg| 183ms| 184ms | 1ms | 0.546
| | P99| 623ms| 500ms | -123ms | -19.759
| uploadFileStream | Avg| 454ms| 442ms | -12ms | -2.644
| | P99| 995ms| 991ms | -4ms | -0.402
| viewChannel | Avg| 17ms| 18ms | 1ms | 5.851
| | P99| 161ms| 175ms | 14ms | 8.711
