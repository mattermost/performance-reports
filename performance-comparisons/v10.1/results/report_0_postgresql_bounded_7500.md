### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 221ms | 800ms | 579ms | 262.12
| ChannelStore.SearchGroupChannels | avg | 4ms | 13ms | 9ms | 250.10
| ChannelStore.AutocompleteInTeamForSearch | avg | 21ms | 63ms | 42ms | 201.60
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 16ms | 30ms | 14ms | 85.48
| RoleStore.GetByNames | avg | 2ms | 4ms | 2ms | 83.45
| ChannelStore.CreateInitialSidebarCategories | avg | 26ms | 45ms | 19ms | 73.15
| ChannelStore.GetSidebarCategory | avg | 10ms | 17ms | 7ms | 69.14
| ChannelStore.CreateSidebarCategory | avg | 27ms | 43ms | 16ms | 60.05
| UserStore.GetProfilesNotInChannel | avg | 6ms | 9ms | 3ms | 54.24
| ChannelStore.Save | avg | 10ms | 13ms | 3ms | 30.43
| TeamStore.GetTotalMemberCount | avg | 25ms | 32ms | 7ms | 27.66
| UserStore.GetProfilesInChannel | avg | 13ms | 16ms | 3ms | 22.61
| ChannelStore.UpdateSidebarCategories | avg | 65ms | 74ms | 9ms | 13.80
| PostStore.SearchPostsForUser | avg | 127ms | 143ms | 16ms | 12.55
| TeamStore.GetActiveMemberCount | avg | 50ms | 52ms | 2ms | 4.01
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 126ms | 3.338s | 3.212s | 2559.08
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 49ms | 39ms | 391.96
| BotStore.Get | p99 | 5ms | 24ms | 19ms | 383.84
| PostStore.GetPostReminderMetadata | p99 | 5ms | 22ms | 17ms | 343.37
| JobStore.UpdateStatus | p99 | 5ms | 18ms | 13ms | 262.63
| ChannelStore.Save | p99 | 37ms | 124ms | 87ms | 233.59
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.67
| UserStore.Update | p99 | 19ms | 44ms | 25ms | 131.06
| PostStore.AnalyticsPostCount | p99 | 495ms | 995ms | 500ms | 101.01
| TeamStore.GetActiveMemberCount | p99 | 50ms | 99ms | 49ms | 98.20
| RoleStore.GetByNames | p99 | 23ms | 45ms | 22ms | 97.35
| UserStore.GetProfilesInChannel | p99 | 25ms | 49ms | 24ms | 96.58
| TeamStore.GetTotalMemberCount | p99 | 50ms | 97ms | 47ms | 94.47
| JobStore.Get | p99 | 5ms | 8ms | 3ms | 60.61
| PostStore.Update | p99 | 50ms | 80ms | 30ms | 59.43
| ChannelStore.GetPublicChannelsForTeam | p99 | 49ms | 73ms | 24ms | 48.49
| ChannelStore.GetPinnedPostCount | p99 | 9ms | 13ms | 4ms | 45.20
| LinkMetadataStore.Save | p99 | 16ms | 22ms | 6ms | 38.21
| ChannelStore.SearchGroupChannels | p99 | 30ms | 37ms | 7ms | 23.43
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 34ms | 41ms | 7ms | 20.85
| StatusStore.SaveOrUpdate | p99 | 311ms | 368ms | 57ms | 18.33
| FileInfoStore.AttachToPost | p99 | 28ms | 33ms | 5ms | 17.98
| PostPriorityStore.GetForPost | p99 | 34ms | 40ms | 6ms | 17.65
| ChannelStore.GetSidebarCategory | p99 | 45ms | 50ms | 5ms | 11.11
| JobStore.GetAllByStatus | p99 | 20ms | 22ms | 2ms | 10.08
| PostStore.GetPostReminders | p99 | 22ms | 24ms | 2ms | 8.91
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 93ms | 97ms | 4ms | 4.32
| UserStore.AutocompleteUsersInChannel | p99 | 315ms | 328ms | 13ms | 4.13
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 3ms | 0s | -3ms | -115.87
| ChannelStore.AnalyticsTypeCount | avg | 8ms | 0s | -8ms | -104.34
| ChannelStore.GetMembersForUserWithPagination | avg | 7ms | 0s | -7ms | -101.86
| UserStore.AnalyticsActiveCount | avg | 19ms | 0s | -19ms | -101.24
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 73ms | 0s | -73ms | -100.40
| PreferenceStore.DeleteCategoryAndName | avg | 8ms | 3ms | -5ms | -64.90
| PluginStore.List | avg | 3ms | 1ms | -2ms | -64.57
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 11ms | 5ms | -6ms | -54.91
| ChannelStore.GetTeamChannels | avg | 20ms | 14ms | -6ms | -29.44
| StatusStore.SaveOrUpdate | avg | 21ms | 17ms | -4ms | -19.23
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 21ms | 18ms | -3ms | -14.40
| ProductNoticesStore.View | avg | 41ms | 36ms | -5ms | -12.34
| ChannelStore.CreateDirectChannel | avg | 24ms | 21ms | -3ms | -12.32
| UserStore.GetAllProfilesInChannel | avg | 255ms | 232ms | -23ms | -9.03
| ChannelStore.SaveMember | avg | 34ms | 31ms | -3ms | -8.79
| UserStore.AutocompleteUsersInChannel | avg | 48ms | 45ms | -3ms | -6.19
| UserStore.Save | avg | 75ms | 73ms | -2ms | -2.68
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| ComplianceStore.MessageExport | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 0s | -5ms | -100.94
| UserStore.AnalyticsActiveCount | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.GetMembersForUserWithPagination | p99 | 10ms | 0s | -10ms | -100.50
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 100ms | 0s | -100ms | -100.50
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 0s | -10ms | -100.45
| PreferenceStore.DeleteCategoryAndName | p99 | 95ms | 5ms | -90ms | -95.24
| PluginStore.List | p99 | 82ms | 8ms | -74ms | -90.24
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 95ms | 10ms | -85ms | -89.95
| FileInfoStore.GetByIds | p99 | 37ms | 7ms | -30ms | -81.63
| StatusStore.GetByIds | p99 | 24ms | 5ms | -19ms | -80.76
| ChannelStore.UpdateSidebarCategories | p99 | 442ms | 100ms | -342ms | -77.29
| JobStore.GetNewestJobByStatusesAndType | p99 | 21ms | 5ms | -16ms | -75.96
| ChannelStore.GetChannelUnread | p99 | 21ms | 5ms | -16ms | -75.83
| PostStore.GetPostsAfter | p99 | 21ms | 5ms | -16ms | -74.76
| JobStore.Save | p99 | 22ms | 9ms | -13ms | -60.12
| ThreadStore.MarkAllAsReadByChannels | p99 | 21ms | 9ms | -12ms | -56.88
| ChannelStore.CreateDirectChannel | p99 | 221ms | 98ms | -123ms | -55.72
| ClusterDiscoveryStore.SetLastPingAt | p99 | 35ms | 16ms | -19ms | -54.03
| JobStore.UpdateOptimistically | p99 | 37ms | 18ms | -19ms | -51.35
| JobStore.GetCountByStatusAndType | p99 | 36ms | 18ms | -18ms | -50.70
| DraftStore.GetDraftsForUser | p99 | 32ms | 16ms | -16ms | -50.35
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 18ms | 10ms | -8ms | -45.54
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 15ms | 8ms | -7ms | -45.50
| TeamStore.GetMember | p99 | 16ms | 9ms | -7ms | -44.68
| ChannelStore.GetChannelsByUser | p99 | 34ms | 19ms | -15ms | -44.45
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 10ms | -8ms | -44.20
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -42.33
| ThreadStore.MaintainMembership | p99 | 43ms | 25ms | -18ms | -41.97
| PostStore.Get | p99 | 43ms | 25ms | -18ms | -41.65
| ChannelStore.GetMember | p99 | 43ms | 25ms | -18ms | -41.58
| PostPersistentNotificationStore.GetSingle | p99 | 17ms | 10ms | -7ms | -41.05
| TeamStore.GetTeamsForUser | p99 | 39ms | 24ms | -15ms | -38.05
| StatusStore.Get | p99 | 35ms | 22ms | -13ms | -36.67
| EmojiStore.GetByName | p99 | 20ms | 13ms | -7ms | -35.58
| TeamStore.Get | p99 | 14ms | 9ms | -5ms | -34.92
| ThreadStore.UpdateMembership | p99 | 17ms | 11ms | -6ms | -34.74
| GroupStore.GetByName | p99 | 38ms | 25ms | -13ms | -34.35
| PostStore.Save | p99 | 82ms | 54ms | -28ms | -34.02
| ReactionStore.GetForPost | p99 | 15ms | 10ms | -5ms | -34.01
| ThreadStore.GetTeamsUnreadForUser | p99 | 41ms | 27ms | -14ms | -33.97
| FileInfoStore.Save | p99 | 33ms | 22ms | -11ms | -32.92
| SessionStore.Get | p99 | 73ms | 49ms | -24ms | -32.90
| TeamStore.GetAllPage | p99 | 34ms | 23ms | -11ms | -32.31
| DraftStore.Get | p99 | 19ms | 13ms | -6ms | -31.81
| PluginStore.SetWithOptions | p99 | 45ms | 31ms | -14ms | -31.00
| ThreadStore.GetThreadForUser | p99 | 36ms | 25ms | -11ms | -30.68
| ChannelStore.GetMemberLastViewedAt | p99 | 33ms | 23ms | -10ms | -30.61
| ChannelStore.GetFileCount | p99 | 23ms | 16ms | -7ms | -30.44
| UserStore.UpdateFailedPasswordAttempts | p99 | 39ms | 27ms | -12ms | -30.38
| TeamStore.SaveMember | p99 | 137ms | 98ms | -39ms | -28.52
| PostAcknowledgementStore.GetForPost | p99 | 29ms | 21ms | -8ms | -27.12
| FileInfoStore.SetContent | p99 | 49ms | 36ms | -13ms | -26.62
| AuditStore.Save | p99 | 38ms | 28ms | -10ms | -26.46
| UserStore.GetForLogin | p99 | 34ms | 25ms | -9ms | -26.33
| PostAcknowledgementStore.GetForPosts | p99 | 23ms | 17ms | -6ms | -25.66
| ChannelStore.Get | p99 | 31ms | 23ms | -8ms | -25.65
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 32ms | 24ms | -8ms | -25.10
| TeamStore.GetTeamsByUserId | p99 | 32ms | 24ms | -8ms | -24.74
| UserStore.IsEmpty | p99 | 21ms | 16ms | -5ms | -24.38
| PostPriorityStore.GetForPosts | p99 | 25ms | 19ms | -6ms | -24.19
| ThreadStore.MarkAsRead | p99 | 17ms | 13ms | -4ms | -23.77
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 21ms | 16ms | -5ms | -23.63
| PreferenceStore.GetAll | p99 | 38ms | 29ms | -9ms | -23.53
| SystemStore.GetByName | p99 | 30ms | 23ms | -7ms | -23.29
| StatusStore.UpdateLastActivityAt | p99 | 22ms | 17ms | -5ms | -22.90
| PreferenceStore.Save | p99 | 92ms | 71ms | -21ms | -22.89
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 31ms | 24ms | -7ms | -22.79
| PostStore.GetPostIdBeforeTime | p99 | 22ms | 17ms | -5ms | -22.75
| ChannelStore.GetGuestCount | p99 | 41ms | 32ms | -9ms | -22.03
| SessionStore.GetLRUSessions | p99 | 28ms | 22ms | -6ms | -21.36
| UserStore.GetProfileByIds | p99 | 29ms | 23ms | -6ms | -20.64
| PluginStore.Delete | p99 | 24ms | 19ms | -5ms | -20.57
| UserStore.UpdateLastLogin | p99 | 30ms | 24ms | -6ms | -20.15
| PostStore.GetPosts | p99 | 30ms | 24ms | -6ms | -20.13
| UserStore.Get | p99 | 20ms | 16ms | -4ms | -19.69
| ChannelStore.IncrementMentionCount | p99 | 27ms | 22ms | -5ms | -18.56
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 28ms | 23ms | -5ms | -18.08
| PostStore.GetPostIdAfterTime | p99 | 28ms | 23ms | -5ms | -18.00
| ThreadStore.GetThreadFollowers | p99 | 22ms | 18ms | -4ms | -17.93
| FileInfoStore.Get | p99 | 11ms | 9ms | -2ms | -17.86
| UserStore.GetProfilesByUsernames | p99 | 22ms | 18ms | -4ms | -17.85
| PostStore.GetEtag | p99 | 28ms | 23ms | -5ms | -17.80
| UserTermsOfServiceStore.GetByUser | p99 | 28ms | 23ms | -5ms | -17.64
| ChannelStore.GetByName | p99 | 46ms | 38ms | -8ms | -17.57
| UserStore.UpdateUpdateAt | p99 | 29ms | 24ms | -5ms | -17.14
| PreferenceStore.Get | p99 | 23ms | 19ms | -4ms | -17.10
| ChannelStore.SaveMember | p99 | 211ms | 175ms | -36ms | -17.07
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 24ms | 20ms | -4ms | -16.67
| ChannelStore.GetAllChannelMembersForUser | p99 | 30ms | 25ms | -5ms | -16.50
| LinkMetadataStore.Get | p99 | 12ms | 10ms | -2ms | -16.48
| ChannelStore.GetMemberForPost | p99 | 26ms | 22ms | -4ms | -15.39
| DraftStore.Upsert | p99 | 26ms | 22ms | -4ms | -15.21
| ChannelStore.GetMembersForUser | p99 | 26ms | 22ms | -4ms | -15.12
| ThreadStore.GetTotalThreads | p99 | 27ms | 23ms | -4ms | -14.89
| ThreadStore.GetMembershipForUser | p99 | 21ms | 18ms | -3ms | -14.32
| ThreadStore.GetTotalUnreadMentions | p99 | 28ms | 24ms | -4ms | -14.05
| UserStore.GetUnreadCount | p99 | 22ms | 19ms | -3ms | -13.78
| SessionStore.UpdateLastActivityAt | p99 | 22ms | 19ms | -3ms | -13.63
| ProductNoticesStore.View | p99 | 244ms | 211ms | -33ms | -13.55
| ChannelStore.UpdateLastViewedAt | p99 | 23ms | 20ms | -3ms | -12.92
| GroupStore.GetGroups | p99 | 24ms | 21ms | -3ms | -12.59
| ChannelStore.GetChannels | p99 | 24ms | 21ms | -3ms | -12.49
| SessionStore.Save | p99 | 48ms | 42ms | -6ms | -12.48
| ThreadStore.GetTotalUnreadThreads | p99 | 26ms | 23ms | -3ms | -11.35
| ChannelStore.GetMemberCount | p99 | 83ms | 74ms | -9ms | -10.83
| UserStore.GetAllProfilesInChannel | p99 | 920ms | 833ms | -87ms | -9.46
| PostStore.GetPostsSince | p99 | 72ms | 66ms | -6ms | -8.33
| UserStore.GetAllProfiles | p99 | 24ms | 22ms | -2ms | -8.21
| PostStore.GetPostsBefore | p99 | 24ms | 22ms | -2ms | -8.20
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 212ms | 197ms | -15ms | -7.07
| ChannelStore.CreateInitialSidebarCategories | p99 | 195ms | 184ms | -11ms | -5.64
| WebhookStore.GetOutgoingByTeam | p99 | 38ms | 36ms | -2ms | -5.32
| UserStore.Save | p99 | 231ms | 221ms | -10ms | -4.32
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchGroupChannels | avg | 4ms | 13ms | 9ms | 245.41
| autocompleteChannelsForTeamForSearch | avg | 21ms | 63ms | 42ms | 201.06
| patchPost | avg | 34ms | 68ms | 34ms | 99.04
| getCategoriesForTeamForUser | avg | 17ms | 31ms | 14ms | 83.13
| createCategoryForTeamForUser | avg | 28ms | 44ms | 16ms | 57.19
| logout | avg | 47ms | 67ms | 20ms | 42.96
| updateCategoriesForTeamForUser | avg | 88ms | 109ms | 21ms | 23.97
| searchPostsInTeam | avg | 132ms | 148ms | 16ms | 12.10
| createChannel | avg | 283ms | 300ms | 17ms | 6.02
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 126ms | 3.338s | 3.212s | 2559.08
| patchPost | p99 | 510ms | 3.075s | 2.565s | 503.12
| getChannel | p99 | 40ms | 83ms | 43ms | 108.17
| createChannel | p99 | 498ms | 975ms | 477ms | 95.88
| setPostReminder | p99 | 25ms | 48ms | 23ms | 92.53
| unfollowThreadByUser | p99 | 25ms | 44ms | 19ms | 76.43
| getPublicChannelsForTeam | p99 | 50ms | 73ms | 23ms | 46.39
| createGroupChannel | p99 | 986ms | 1.345s | 359ms | 36.42
| searchGroupChannels | p99 | 30ms | 37ms | 7ms | 23.43
| getTeamMember | p99 | 21ms | 25ms | 4ms | 18.97
| uploadFileStream | p99 | 1.006s | 1.147s | 141ms | 14.02
| autocompleteUsers | p99 | 262ms | 273ms | 11ms | 4.19
| logout | p99 | 97ms | 100ms | 3ms | 3.08
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 13ms | 0s | -13ms | -97.69
| createDirectChannel | avg | 341ms | 224ms | -117ms | -34.27
| createGroupChannel | avg | 490ms | 356ms | -134ms | -27.34
| addChannelMember | avg | 277ms | 207ms | -70ms | -25.31
| createUser | avg | 175ms | 137ms | -38ms | -21.68
| login | avg | 94ms | 74ms | -20ms | -21.34
| getPostsForChannelAroundLastUnread | avg | 20ms | 16ms | -4ms | -20.39
| addTeamMember | avg | 919ms | 844ms | -75ms | -8.16
| removeUserCustomStatus | avg | 179ms | 165ms | -14ms | -7.80
| getProfileImage | avg | 87ms | 81ms | -6ms | -6.93
| autocompleteUsers | avg | 44ms | 41ms | -3ms | -6.88
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| submitPerformanceReport | p99 | 5ms | 0s | -5ms | -101.01
| getRolesByNames | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| getJobsByType | p99 | 7ms | 0s | -7ms | -95.92
| getChannelUnread | p99 | 21ms | 5ms | -16ms | -75.83
| getDrafts | p99 | 33ms | 16ms | -17ms | -52.06
| createDirectChannel | p99 | 984ms | 494ms | -490ms | -49.82
| getPostThread | p99 | 71ms | 36ms | -35ms | -49.55
| getChannelsForUser | p99 | 36ms | 19ms | -17ms | -47.23
| updatePreferences | p99 | 46ms | 25ms | -21ms | -46.06
| updateCategoriesForTeamForUser | p99 | 442ms | 249ms | -193ms | -43.62
| getUser | p99 | 74ms | 42ms | -32ms | -43.36
| getChannelsForTeamForUser | p99 | 39ms | 22ms | -17ms | -43.31
| createPost | p99 | 1.794s | 1.034s | -760ms | -42.36
| createUser | p99 | 811ms | 475ms | -336ms | -41.43
| getAllTeams | p99 | 44ms | 26ms | -18ms | -41.38
| getUsers | p99 | 69ms | 41ms | -28ms | -40.69
| getChannelMembersForTeamForUser | p99 | 38ms | 23ms | -15ms | -39.35
| getTeamMembersForUser | p99 | 57ms | 35ms | -22ms | -38.37
| viewChannel | p99 | 82ms | 52ms | -30ms | -36.51
| getChannelMember | p99 | 95ms | 61ms | -34ms | -35.82
| getPostsForChannelAroundLastUnread | p99 | 204ms | 131ms | -73ms | -35.77
| saveReaction | p99 | 76ms | 49ms | -27ms | -35.45
| upsertDraft | p99 | 36ms | 24ms | -12ms | -33.32
| getTeamsForUser | p99 | 35ms | 24ms | -11ms | -31.40
| addChannelMember | p99 | 712ms | 489ms | -223ms | -31.30
| getTeamsUnreadForUser | p99 | 58ms | 40ms | -18ms | -30.88
| getThreadsForUser | p99 | 36ms | 25ms | -11ms | -30.19
| deleteDraft | p99 | 20ms | 14ms | -6ms | -29.64
| getClientConfig | p99 | 90ms | 66ms | -24ms | -26.69
| login | p99 | 557ms | 422ms | -135ms | -24.26
| getUsersByNames | p99 | 23ms | 18ms | -5ms | -21.63
| getPreferences | p99 | 42ms | 33ms | -9ms | -21.62
| updateReadStateThreadByUser | p99 | 177ms | 141ms | -36ms | -20.33
| addTeamMember | p99 | 2.917s | 2.444s | -473ms | -16.22
| getPostsForChannel | p99 | 194ms | 172ms | -22ms | -11.32
| getChannelStats | p99 | 49ms | 46ms | -3ms | -6.15
| getProfileImage | p99 | 456ms | 442ms | -14ms | -3.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 28ms | -10ms | -26.463
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 54.988
| |  P99| 5ms| 24ms | 19ms | 383.838
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 73ms| 0s | -73ms | -100.403
| |  P99| 100ms| 0s | -100ms | -100.503
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 4ms | -1ms | -21.878
| |  P99| 28ms| 23ms | -5ms | -18.077
| ChannelStore.AnalyticsTypeCount |  Avg| 8ms| 0s | -8ms | -104.339
| |  P99| 10ms| 0s | -10ms | -100.446
| ChannelStore.Autocomplete |  Avg| 45ms| 44ms | -1ms | -2.246
| |  P99| 100ms| 99ms | -1ms | -1.005
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 21ms| 63ms | 42ms | 201.599
| |  P99| 126ms| 3.338s | 3.212s | 2559.079
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 21ms | -3ms | -12.322
| |  P99| 221ms| 98ms | -123ms | -55.716
| ChannelStore.CreateInitialSidebarCategories |  Avg| 26ms| 45ms | 19ms | 73.150
| |  P99| 195ms| 184ms | -11ms | -5.643
| ChannelStore.CreateSidebarCategory |  Avg| 27ms| 43ms | 16ms | 60.049
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 23ms | -8ms | -25.648
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 34ms| 41ms | 7ms | 20.847
| ChannelStore.GetAllChannelMembersForUser |  Avg| 6ms| 5ms | -1ms | -18.006
| |  P99| 30ms| 25ms | -5ms | -16.496
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 21ms| 18ms | -3ms | -14.397
| |  P99| 212ms| 197ms | -15ms | -7.066
| ChannelStore.GetByName |  Avg| 5ms| 4ms | -1ms | -21.728
| |  P99| 46ms| 38ms | -8ms | -17.571
| ChannelStore.GetChannelUnread |  Avg| 2ms| 1ms | -1ms | -57.244
| |  P99| 21ms| 5ms | -16ms | -75.834
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.494
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 19ms | -15ms | -44.448
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 1ms | -1ms | -59.483
| |  P99| 21ms| 16ms | -5ms | -23.627
| ChannelStore.GetFileCount |  Avg| 3ms| 2ms | -1ms | -38.808
| |  P99| 23ms| 16ms | -7ms | -30.440
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 32ms | -9ms | -22.027
| ChannelStore.GetMember |  Avg| 5ms| 4ms | -1ms | -21.412
| |  P99| 43ms| 25ms | -18ms | -41.583
| ChannelStore.GetMemberCount |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 83ms| 74ms | -9ms | -10.828
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 26ms| 22ms | -4ms | -15.391
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 33ms| 23ms | -10ms | -30.614
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 22ms | -4ms | -15.122
| ChannelStore.GetMembersForUserWithPagination |  Avg| 7ms| 0s | -7ms | -101.858
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 45.197
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 49ms| 73ms | 24ms | 48.487
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 16ms| 30ms | 14ms | 85.476
| |  P99| 93ms| 97ms | 4ms | 4.324
| ChannelStore.GetSidebarCategory |  Avg| 10ms| 17ms | 7ms | 69.143
| |  P99| 45ms| 50ms | 5ms | 11.111
| ChannelStore.GetTeamChannels |  Avg| 20ms| 14ms | -6ms | -29.438
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 22ms | -5ms | -18.559
| ChannelStore.Save |  Avg| 10ms| 13ms | 3ms | 30.430
| |  P99| 37ms| 124ms | 87ms | 233.588
| ChannelStore.SaveMember |  Avg| 34ms| 31ms | -3ms | -8.793
| |  P99| 211ms| 175ms | -36ms | -17.066
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 13ms | 9ms | 250.098
| |  P99| 30ms| 37ms | 7ms | 23.432
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -12.918
| ChannelStore.UpdateSidebarCategories |  Avg| 65ms| 74ms | 9ms | 13.796
| |  P99| 442ms| 100ms | -342ms | -77.291
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 8ms | -7ms | -45.504
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 4ms | -1ms | -21.965
| |  P99| 35ms| 16ms | -19ms | -54.026
| CommandWebhookStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 49.772
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 0s | -3ms | -115.870
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.358
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 11ms| 5ms | -6ms | -54.912
| |  P99| 95ms| 10ms | -85ms | -89.946
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 13ms | -6ms | -31.813
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -38.115
| |  P99| 32ms| 16ms | -16ms | -50.349
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 22ms | -4ms | -15.214
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 13ms | -7ms | -35.583
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 8ms | 1ms | 13.827
| |  P99| 28ms| 33ms | 5ms | 17.981
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.864
| FileInfoStore.GetByIds |  Avg| 2ms| 1ms | -1ms | -51.257
| |  P99| 37ms| 7ms | -30ms | -81.628
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.296
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 22ms | -11ms | -32.919
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.283
| |  P99| 49ms| 36ms | -13ms | -26.615
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 1ms | -1ms | -57.189
| |  P99| 24ms| 20ms | -4ms | -16.669
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 25ms | -13ms | -34.346
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.591
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.GetAllByStatus |  Avg| 1ms| 2ms | 1ms | 67.811
| |  P99| 20ms| 22ms | 2ms | 10.080
| JobStore.GetAllByTypePage |  Avg| 1ms| 0s | -1ms | -115.515
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 1ms | -1ms | -46.399
| |  P99| 36ms| 18ms | -18ms | -50.704
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 1ms | -1ms | -55.627
| |  P99| 21ms| 5ms | -16ms | -75.964
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 9ms | -13ms | -60.116
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 18ms | -19ms | -51.351
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -44.199
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -188.853
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.485
| LinkMetadataStore.Save |  Avg| 4ms| 5ms | 1ms | 25.673
| |  P99| 16ms| 22ms | 6ms | 38.211
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 19ms | -5ms | -20.568
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -127.450
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 3ms| 1ms | -2ms | -64.566
| |  P99| 82ms| 8ms | -74ms | -90.244
| PluginStore.SetWithOptions |  Avg| 7ms| 6ms | -1ms | -13.880
| |  P99| 45ms| 31ms | -14ms | -31.002
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -64.878
| |  P99| 29ms| 21ms | -8ms | -27.119
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 17ms | -6ms | -25.662
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -41.047
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 40ms | 6ms | 17.646
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 19ms | -6ms | -24.191
| PostStore.AnalyticsPostCount |  Avg| 221ms| 800ms | 579ms | 262.124
| |  P99| 495ms| 995ms | 500ms | 101.009
| PostStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 25ms | -18ms | -41.649
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 23ms | -5ms | -17.800
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 23ms | -5ms | -18.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 2ms | -1ms | -37.589
| |  P99| 22ms| 17ms | -5ms | -22.751
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 3ms | 1ms | 50.888
| |  P99| 5ms| 22ms | 17ms | 343.366
| PostStore.GetPostReminders |  Avg| 6ms| 7ms | 1ms | 15.983
| |  P99| 22ms| 24ms | 2ms | 8.909
| PostStore.GetPosts |  Avg| 4ms| 3ms | -1ms | -27.248
| |  P99| 30ms| 24ms | -6ms | -20.135
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -37.886
| |  P99| 21ms| 5ms | -16ms | -74.763
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.205
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 72ms| 66ms | -6ms | -8.326
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.115
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 13ms | -1ms | -7.054
| |  P99| 82ms| 54ms | -28ms | -34.015
| PostStore.SearchPostsForUser |  Avg| 127ms| 143ms | 16ms | 12.549
| |  P99| 2.205s| 2.211s | 6ms | 0.272
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 14.343
| |  P99| 10ms| 24ms | 14ms | 140.673
| PostStore.Update |  Avg| 16ms| 17ms | 1ms | 6.446
| |  P99| 50ms| 80ms | 30ms | 59.428
| PreferenceStore.DeleteCategoryAndName |  Avg| 8ms| 3ms | -5ms | -64.901
| |  P99| 95ms| 5ms | -90ms | -95.237
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.101
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 29ms | -9ms | -23.531
| PreferenceStore.Save |  Avg| 13ms| 12ms | -1ms | -7.478
| |  P99| 92ms| 71ms | -21ms | -22.894
| ProductNoticesStore.ClearOldNotices |  Avg| 20ms| 19ms | -1ms | -5.073
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 0s | -1ms | -89.578
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 41ms| 36ms | -5ms | -12.345
| |  P99| 244ms| 211ms | -33ms | -13.546
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -34.011
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -77.193
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.514
| RoleStore.GetByNames |  Avg| 2ms| 4ms | 2ms | 83.446
| |  P99| 23ms| 45ms | 22ms | 97.345
| SessionStore.Get |  Avg| 7ms| 6ms | -1ms | -14.821
| |  P99| 73ms| 49ms | -24ms | -32.904
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 22ms | -6ms | -21.365
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 1ms | -1ms | -65.091
| |  P99| 18ms| 10ms | -8ms | -45.535
| SessionStore.Remove |  Avg| 4ms| 3ms | -1ms | -28.016
| |  P99| 9ms| 5ms | -4ms | -42.329
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 48ms| 42ms | -6ms | -12.483
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.633
| StatusStore.Get |  Avg| 2ms| 1ms | -1ms | -45.855
| |  P99| 35ms| 22ms | -13ms | -36.667
| StatusStore.GetByIds |  Avg| 2ms| 1ms | -1ms | -55.501
| |  P99| 24ms| 5ms | -19ms | -80.761
| StatusStore.SaveOrUpdate |  Avg| 21ms| 17ms | -4ms | -19.225
| |  P99| 311ms| 368ms | 57ms | 18.326
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.444
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 17ms | -5ms | -22.902
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 23ms | -7ms | -23.291
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 0s | -1ms | -107.163
| |  P99| 5ms| 0s | -5ms | -100.942
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -34.920
| TeamStore.GetActiveMemberCount |  Avg| 50ms| 52ms | 2ms | 4.011
| |  P99| 50ms| 99ms | 49ms | 98.197
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 23ms | -11ms | -32.311
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 2ms | -1ms | -37.281
| |  P99| 32ms| 24ms | -8ms | -25.105
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -44.684
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 24ms | -8ms | -24.744
| TeamStore.GetTeamsForUser |  Avg| 3ms| 2ms | -1ms | -37.646
| |  P99| 39ms| 24ms | -15ms | -38.055
| TeamStore.GetTotalMemberCount |  Avg| 25ms| 32ms | 7ms | 27.655
| |  P99| 50ms| 97ms | 47ms | 94.472
| TeamStore.SaveMember |  Avg| 31ms| 30ms | -1ms | -3.196
| |  P99| 137ms| 98ms | -39ms | -28.523
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.321
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 27ms | -14ms | -33.965
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -17.930
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 36ms| 25ms | -11ms | -30.680
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.069
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.117
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 23ms | -4ms | -14.892
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.049
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 26ms| 23ms | -3ms | -11.347
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 2ms | -1ms | -37.832
| |  P99| 31ms| 24ms | -7ms | -22.794
| ThreadStore.MaintainMembership |  Avg| 7ms| 6ms | -1ms | -14.663
| |  P99| 43ms| 25ms | -18ms | -41.973
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -56.876
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 13ms | -4ms | -23.774
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 11ms | -6ms | -34.743
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.673
| UserStore.AnalyticsActiveCount |  Avg| 19ms| 0s | -19ms | -101.239
| |  P99| 25ms| 0s | -25ms | -100.604
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 0s | -1ms | -192.915
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 48ms| 45ms | -3ms | -6.187
| |  P99| 315ms| 328ms | 13ms | 4.129
| UserStore.Count |  Avg| 13ms| 14ms | 1ms | 7.808
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -19.693
| UserStore.GetAllProfiles |  Avg| 4ms| 3ms | -1ms | -26.331
| |  P99| 24ms| 22ms | -2ms | -8.214
| UserStore.GetAllProfilesInChannel |  Avg| 255ms| 232ms | -23ms | -9.026
| |  P99| 920ms| 833ms | -87ms | -9.455
| UserStore.GetByUsername |  Avg| 2ms| 1ms | -1ms | -66.261
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 3ms| 2ms | -1ms | -38.339
| |  P99| 34ms| 25ms | -9ms | -26.327
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 2ms | -1ms | -39.311
| |  P99| 29ms| 23ms | -6ms | -20.639
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -17.845
| UserStore.GetProfilesInChannel |  Avg| 13ms| 16ms | 3ms | 22.606
| |  P99| 25ms| 49ms | 24ms | 96.579
| UserStore.GetProfilesNotInChannel |  Avg| 6ms| 9ms | 3ms | 54.240
| |  P99| 10ms| 49ms | 39ms | 391.960
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.778
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -24.378
| UserStore.Save |  Avg| 75ms| 73ms | -2ms | -2.677
| |  P99| 231ms| 221ms | -10ms | -4.321
| UserStore.Search |  Avg| 36ms| 35ms | -1ms | -2.772
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 8ms | 1ms | 13.749
| |  P99| 19ms| 44ms | 25ms | 131.056
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 5ms | -1ms | -17.965
| |  P99| 39ms| 27ms | -12ms | -30.382
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 30ms| 24ms | -6ms | -20.147
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 29ms| 24ms | -5ms | -17.143
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 23ms | -5ms | -17.642
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.317
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 277ms| 207ms | -70ms | -25.312
| | P99| 712ms| 489ms | -223ms | -31.299
| addTeamMember | Avg| 919ms| 844ms | -75ms | -8.162
| | P99| 2.917s| 2.444s | -473ms | -16.217
| autocompleteChannelsForTeamForSearch | Avg| 21ms| 63ms | 42ms | 201.055
| | P99| 126ms| 3.338s | 3.212s | 2559.079
| autocompleteUsers | Avg| 44ms| 41ms | -3ms | -6.877
| | P99| 262ms| 273ms | 11ms | 4.192
| createCategoryForTeamForUser | Avg| 28ms| 44ms | 16ms | 57.189
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 283ms| 300ms | 17ms | 6.017
| | P99| 498ms| 975ms | 477ms | 95.879
| createDirectChannel | Avg| 341ms| 224ms | -117ms | -34.266
| | P99| 984ms| 494ms | -490ms | -49.817
| createGroupChannel | Avg| 490ms| 356ms | -134ms | -27.336
| | P99| 986ms| 1.345s | 359ms | 36.425
| createPost | Avg| 318ms| 315ms | -3ms | -0.944
| | P99| 1.794s| 1.034s | -760ms | -42.362
| createUser | Avg| 175ms| 137ms | -38ms | -21.679
| | P99| 811ms| 475ms | -336ms | -41.428
| deleteDraft | Avg| 2ms| 1ms | -1ms | -63.879
| | P99| 20ms| 14ms | -6ms | -29.638
| deletePost | Avg| 19ms| 18ms | -1ms | -5.261
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 2ms | -1ms | -32.198
| | P99| 44ms| 26ms | -18ms | -41.378
| getCategoriesForTeamForUser | Avg| 17ms| 31ms | 14ms | 83.127
| | P99| 97ms| 97ms | 0s | 0.000
| getChannel | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 40ms| 83ms | 43ms | 108.174
| getChannelMember | Avg| 8ms| 7ms | -1ms | -11.931
| | P99| 95ms| 61ms | -34ms | -35.823
| getChannelMembersForTeamForUser | Avg| 4ms| 3ms | -1ms | -27.287
| | P99| 38ms| 23ms | -15ms | -39.347
| getChannelStats | Avg| 4ms| 3ms | -1ms | -28.114
| | P99| 49ms| 46ms | -3ms | -6.153
| getChannelUnread | Avg| 2ms| 1ms | -1ms | -43.828
| | P99| 21ms| 5ms | -16ms | -75.834
| getChannelsForTeamForUser | Avg| 3ms| 2ms | -1ms | -31.015
| | P99| 39ms| 22ms | -17ms | -43.314
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 36ms| 19ms | -17ms | -47.225
| getClientConfig | Avg| 9ms| 8ms | -1ms | -10.575
| | P99| 90ms| 66ms | -24ms | -26.690
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 3ms| 2ms | -1ms | -36.469
| | P99| 33ms| 16ms | -17ms | -52.057
| getFilePreview | Avg| 46ms| 47ms | 1ms | 2.164
| | P99| 221ms| 222ms | 1ms | 0.452
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 97ms| 97ms | 0s | 0.000
| getFilteredUsersStats | Avg| 13ms| 0s | -13ms | -97.689
| | P99| 25ms| 0s | -25ms | -100.604
| getJobsByType | Avg| 1ms| 0s | -1ms | -94.373
| | P99| 7ms| 0s | -7ms | -95.920
| getPostThread | Avg| 7ms| 6ms | -1ms | -14.720
| | P99| 71ms| 36ms | -35ms | -49.551
| getPostsForChannel | Avg| 19ms| 18ms | -1ms | -5.247
| | P99| 194ms| 172ms | -22ms | -11.315
| getPostsForChannelAroundLastUnread | Avg| 20ms| 16ms | -4ms | -20.395
| | P99| 204ms| 131ms | -73ms | -35.768
| getPreferences | Avg| 4ms| 3ms | -1ms | -27.017
| | P99| 42ms| 33ms | -9ms | -21.620
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -105.308
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 87ms| 81ms | -6ms | -6.927
| | P99| 456ms| 442ms | -14ms | -3.068
| getPublicChannelsForTeam | Avg| 19ms| 20ms | 1ms | 5.277
| | P99| 50ms| 73ms | 23ms | 46.388
| getRolesByNames | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 25ms | 4ms | 18.974
| getTeamMembersForUser | Avg| 4ms| 3ms | -1ms | -24.908
| | P99| 57ms| 35ms | -22ms | -38.371
| getTeamStats | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 100ms| 99ms | -1ms | -1.005
| getTeamsForUser | Avg| 3ms| 2ms | -1ms | -39.582
| | P99| 35ms| 24ms | -11ms | -31.398
| getTeamsUnreadForUser | Avg| 5ms| 4ms | -1ms | -19.638
| | P99| 58ms| 40ms | -18ms | -30.877
| getThreadsForUser | Avg| 4ms| 3ms | -1ms | -26.329
| | P99| 36ms| 25ms | -11ms | -30.192
| getUser | Avg| 4ms| 3ms | -1ms | -23.043
| | P99| 74ms| 42ms | -32ms | -43.359
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 5ms | -1ms | -15.429
| | P99| 69ms| 41ms | -28ms | -40.685
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -11.845
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 23ms| 18ms | -5ms | -21.627
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 94ms| 74ms | -20ms | -21.342
| | P99| 557ms| 422ms | -135ms | -24.256
| logout | Avg| 47ms| 67ms | 20ms | 42.960
| | P99| 97ms| 100ms | 3ms | 3.085
| patchPost | Avg| 34ms| 68ms | 34ms | 99.043
| | P99| 510ms| 3.075s | 2.565s | 503.124
| removeUserCustomStatus | Avg| 179ms| 165ms | -14ms | -7.803
| | P99| 476ms| 478ms | 2ms | 0.421
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 8ms | -1ms | -11.228
| | P99| 76ms| 49ms | -27ms | -35.454
| searchAllChannels | Avg| 45ms| 44ms | -1ms | -2.225
| | P99| 100ms| 99ms | -1ms | -1.004
| searchGroupChannels | Avg| 4ms| 13ms | 9ms | 245.412
| | P99| 30ms| 37ms | 7ms | 23.432
| searchPostsInTeam | Avg| 132ms| 148ms | 16ms | 12.100
| | P99| 2.243s| 2.242s | -1ms | -0.045
| searchUsers | Avg| 38ms| 37ms | -1ms | -2.634
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 17ms | 1ms | 6.289
| | P99| 25ms| 48ms | 23ms | 92.532
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| unfollowThreadByUser | Avg| 12ms| 13ms | 1ms | 8.343
| | P99| 25ms| 44ms | 19ms | 76.432
| updateCategoriesForTeamForUser | Avg| 88ms| 109ms | 21ms | 23.969
| | P99| 442ms| 249ms | -193ms | -43.618
| updatePreferences | Avg| 10ms| 9ms | -1ms | -10.229
| | P99| 46ms| 25ms | -21ms | -46.062
| updateReadStateThreadByUser | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 177ms| 141ms | -36ms | -20.327
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 413ms| 409ms | -4ms | -0.968
| | P99| 1.006s| 1.147s | 141ms | 14.017
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 36ms| 24ms | -12ms | -33.324
| viewChannel | Avg| 10ms| 9ms | -1ms | -10.272
| | P99| 82ms| 52ms | -30ms | -36.505
